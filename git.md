KEEER Git Guide
===============

## WSL是什么？
TODO

## 安装WSL
参考[这篇文章](https://zhuanlan.zhihu.com/p/34885182)。本教程中所有操作均在Debian下进行，也可使用Ubuntu。

## 在WSL中安装Git
### 1. 安装并配置Git
注意：请将`you@example.com`替换为你的邮箱，将`Your Name`替换为你的姓名。
```
sudo apt update
sudo apt install git
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

### 2. 配置SSH
注意：请将`you@example.com`替换为你的邮箱。

```
ssh-keygen -t rsa -b 4096 -C "you@example.com"
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
```

### 3. 配置GPG
我们推荐使用4096位密钥。

注意：请将*`0E76AD10B3B7C66F`*替换为你的`gpg --list-secret-keys --keyid-format LONG`的输出中的内容（见下）。

```
gpg --full-generate-key
gpg --list-secret-keys --keyid-format LONG
gpg --armor --export 0E76AD10B3B7C66F
git config --global user.signingkey 0E76AD10B3B7C66F
git config --global commit.gpgsign true
```

`gpg --list-secret-keys --keyid-format LONG` 输出：

```
gpg: checking the trustdb
gpg: marginals needed: 3  completes needed: 1  trust model: pgp
gpg: depth: 0  valid:   1  signed:   0  trust: 0-, 0q, 0n, 0m, 0f, 1u
/home/alan-liang/.gnupg/pubring.kbx
-----------------------------------
sec   rsa4096/0E76AD10B3B7C66F 2019-05-29 [SC] // 注意0E76AD10B3B7C66F
      0388080D7996FC65483C52800E76AD10B3B7C66F
uid                 [ultimate] Alan-Liang (Alan Liang) <a@keeer.net>
ssb   rsa4096/EF93B4028712D401 2019-05-29 [E]
```

## 测试Git
### 基本操作
```
mkdir hello-git
cd hello-git
git init
echo "Hello Git!" > README.md
git add .
git commit -m "Initial Commit"
git log
```

### Branching
```
git branch feat-foo
git checkout feat-foo
echo "Feature!" > foo.txt
git add .
git commit -m "feat(foo): foo.txt"
git checkout master
```

### Clone现有repo
```
git clone git@github.com:KEEER/guides.git
cd guides
```
