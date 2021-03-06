KEEER 用户界面语言规范
===

格式手册的目的是为了提供一些准则、方针，使得所有 KEEER 提供的服务在用户体验上基本一致。以下的规则并没有声明不能变动，也不暗示这些规则比其他方式都要好，但如果所有人的语言风格都一致，KEEER 的服务会更易于使用。

## 适用范围

本规范适用于 KEEER 所有服务的用户界面上的中文引导性文字，如对话框文字、输入框引导、按钮文字等。本规范不适用于大段文字，如博文、用户协议、公众号推送等。

## 总则

尽量使用正式语言和语气，而非口语。

使用规范的语言文字。

避免开玩笑或使用网络用语。

在中文语境下尽量避免不必要的外语插入。

简洁。

## 用词

很多常用词有一些错误用法，或者多种用法中 KEEER 推荐使用其中一种，这些用法列在附录中。请正确用词。

### 对当前用户的称呼

在完整句中使用敬称「您」，而非「你」、「我」或「阁下」。例外：当用户需要自行点击一个单独的区域以确认一个事件时，使用「我」。

正确示例：
- 请确保充值前您已经悉知并同意 Kredit 条款
- 您在 KEEER 服务中使用的基本信息，点击以编辑它们

正确的例外：
- [复选框] 我已阅读并同意用户协议和隐私政策
- 请确认您的订单信息，[按钮：我确认]

错误的例外（不要这样用）：
- 点击「注册」表示我已阅读并同意用户协议和隐私政策，[按钮：注册]

在短语用做页面标题时，使用「我」。

正确示例：
- 我的帐号
- 我的表单

### 对自己（KEEER）的称呼

在大多数情况下可以回避主语；如要使用主语，使用「我们」或「KEEER」。

正确示例：
- 您的帐号已被封禁

错误示例：
- 我们封禁了您的帐号

### 对服务的称呼

直接称呼服务名称；多次重复时，使用「本服务」而非「该服务」进行指代。

正确示例：
- 请充值以继续使用 Cloud Print
- 开通 Vote Pro 以享受全部功能

不推荐的用法：
- 请充值以继续使用本服务

错误示例：
- 请充值以继续使用该服务

### 链接文本

链接文本两侧各加一个空格（有标点符号的除外）。链接文本应该是页面标题等有意义的内容，不能是「这里」「链接」等词语。

正确示例：
- 您可以参考 [Firefox][fx] 的设计。
- 部分内容来自 [维基百科][wp]。

错误示例：
- 您可以参考[ Firefox][fx] 的设计。
- 部分内容来自[维基百科][wp]。
- 部分内容来自 [这里][wp]。

## 标点符号

- 尽量不使用感叹号「！」。
- 不连续使用标点，如「！！！」「。。。」（使用省略号「……」代替）。
- 在中文语境下使用全角（Em width）标点，即使标点两侧都是西文字母。
- 注意：Microsoft Word 等文字处理软件可能会自动处理标点使得其不符合本规范，在使用此类软件时请特别注意。

正确示例：
- 删除操作是不可恢复的。
- 您的帐号已被封禁。
- Vote 提供了丰富的 API，HTTP 调用即可使用。

错误示例：
- 删除操作是！不！可！恢！复！的！！！
- 您的帐号已被封禁。。。
- Vote 提供了丰富的 API, HTTP 调用即可使用。

下文提到的很多标点符号可以在 [Alan-Liang 的 Unicode collection 里][unicode] 复制。

除下面特殊注明之外，使用一般的规范标点：

### 引号

引号使用直角引号「」而非弯引号“”，即使引文为西文。

正确示例：
- 您的表单「加入 KEEER」已保存。

错误示例：
- 您的表单“加入 KEEER”已保存。

例外：在短信中使用弯引号；当表示引号内内容并非词语本意时使用弯引号（但是，应该尽量避免出现这种情况）。

正确示例：
- Microsoft 是一家“微小的”软件公司。

### 空格

在中文字符和西文字符之间加一个半角（En width）空格（如果条件允许，也可以使用六分之一（Six-per-em）空格）；但是在标点符号两侧无需加空格。

在竖线「|」表示分割时，在两侧各加一个空格。

正确示例：
- Vote 提供了丰富的 API，以供二次开发使用。
- 歌舞嘉年华 | 惜

错误示例：
- Vote 提供了丰富的 API ，以供二次开发使用。
- Vote提供了丰富的API，以供二次开发使用。
- 歌舞嘉年华|惜

## 破折号

使用一个两字长连接号（Two em dash，「⸺」）或者两个全角连接号（Em dash，「——」），推荐使用前者。不要使用多个半角连接号「----」。

## 句式

### 使用主动语气

正确示例：
- 点击下面的按钮以设置 KEEER ID。
- 请充值以继续使用 Cloud Print
- 请您填写一个电话号码

错误示例：
- 您需要充值以继续使用 Cloud Print
- 必须是一个电话号码

例外：有些时候可以使用被动表述以避免提到自己，此时可以使用被动表述。

正确示例：
- 删除操作是不可恢复的。
- 您的帐号已被封禁。
- 您传输的数据全部受到加密。

错误示例：
- 我们无法恢复删除操作。
- 我们封禁了您的帐号。
- 我们加密了全部您传输的数据。

### 正面表达

正确示例：
- 请您填写一个电话号码
- [复选框] 显示高级功能

错误示例：
- 您填写的不是一个电话号码
- [复选框] 隐藏高级功能

### 祈使句和陈述句

提示用户行为不符合预期时，使用祈使句。

正确示例：
- 请您填写一个电话号码
- 请充值以继续使用 Cloud Print

错误示例：
- 必须填写一个电话号码
- 需要充值以继续使用 Cloud Print

引导用户进行操作时，使用陈述句。

正确示例：
- 开通 Vote Pro 以享受全部功能
- 走到打印机前，输入上方的四个数字，即可打印您的文件

错误示例：
- 请开通 Vote Pro，享受全部功能
- 请您走到打印机前，输入上方的四个数字，打印您的文件

## 排版

少用粗体、斜体、特殊颜色、加大字号。

正确示例：    
如果您使用过万圣节鬼屋门票平台，那么您甚至无需注册新的账号。您之前购买门票剩余的充值金额也可用于 Cloud Print。

错误示例：    
如果您使用过**万圣节鬼屋门票平台**，那么您甚至**无需**<font color=red>注册</font>*新的账号*。您之前购买门票剩余的充值金额**也可用**于 Cloud Print。

不用粗体替代标题。

## 附录

### 词汇表

#### 通用

| 正确用词 | 不推荐使用的其他正确用词 | 错误用词 | 备注 |
| :-- | :-- | :-- | :-- |
| iOS |  | ~~IOS~~ |  |
| JavaScript |  | ~~Javascript、javaScript、Java Script~~ |  |
| KEEER | 客页 | ~~KR、KEER、KEEEER~~ |  |
| 帐号 | 帐户 | ~~账号、账户~~ | 「账」字用于财务相关，如「人民币账户」 |
| 登录 | 登入 | ~~登陆~~ |  |
| 注册 | 创建帐号 | ~~登录~~ | 台湾等地区使用「登录」表示注册 |
| 退出登录 | 登出 | ~~注销~~ |  |
| 设置 | 设定、偏好 |  |  |
| 手机号码 | 手机号 | ~~手机~~ |  |
| 图片 | 图 | ~~照片~~ | 「照片」比「图片」概念小 |

#### KAS

产品名：KEEER 帐号服务 / KEEER Account Service

| 正确用词 | 不推荐 | 错误用词 | 备注 |
| :-- | :-- | :-- | :-- |
| KEEER 帐号 |  | ~~KEEER ID~~ |  |
| 昵称 |  | ~~用户名~~ |  |
| Kredit | 信用点 | ~~Credit~~ |  |

#### Vote

| 正确用词 | 不推荐 | 错误用词 | 备注 |
| :-- | :-- | :-- | :-- |
| 表单 |  | ~~问卷~~ | 「问卷」比「表单」概念小 |
| 问题 |  | ~~题目~~ |  |
| 添加问题 | 新建问题、创建问题 | ~~新的问题~~ |  |

## 参见

- [维基百科：格式手册][wp]
- [Grammar and mechanics - Stacks][so]
- [Personality – Mozilla Dot Design][fx]
- [Voice and Tone | Mailchimp Content Style Guide][mc]
- [The Type — 文字/设计/文化 » 不离不弃的破折号][dash]

## 关于本文档

本文档以 CC BY-SA 3.0 协议授权，部分内容来自 [维基百科][wp]。

[wp]: https://zh.wikipedia.org/wiki/Wikipedia:%E6%A0%BC%E5%BC%8F%E6%89%8B%E5%86%8C
[so]: https://stackoverflow.design/content/guidelines/grammar-and-mechanics/
[fx]: https://mozilla.design/firefox/personality/
[mc]: https://styleguide.mailchimp.com/voice-and-tone/
[dash]: https://www.thetype.com/2019/03/14918/
[unicode]: https://lab.olic.link/unicode/
