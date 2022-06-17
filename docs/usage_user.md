## Liteyuki Bot 面向QQ用户使用手册

### 开始

- 发送`help`/`菜单`/`帮助`获取插件列表。
- 发送`help <插件名>`获取单个插件的帮助文档，例如`help 天气`。
- 发送`help <插件名> <子文档>`获取插件的子文档，例如`help 学习工具 语文`。
- 子文档可以是很多层级的，取决于开发者怎么写，例如`help <插件名> <父分类1> <子分类1> <子文档>`。
- 首先，文档中的命令提示参数一般带有`<>`和`[]`，这是表示这个参数的类型，
  `<>`为必填参数，`[]`为可选参数，若出现类似于`[args=]`这样的参数，请将参数值写到等号后面，
  例如`teleport each type=people`。

### 常用命令

- `查询好感度/硬币`
- `/about`(关于机器人)
- `/state`(查看运行设备状态)

### 好感度&硬币系统

- 为了给用户带来更简洁的体验，轻雪机器人只有一种用于互动交易的虚拟代币，称为硬币。
- 轻雪机器人有一个好感度系统，好感度分为1-10级，1000好感度即可满级，具体升级方式请查看下面的表格。
- 每个新用户(不管是否注册)都拥有100个硬币，20好感度。

##### 好感度系统

- 好感度和你在群聊中机器人响应你消息的频率有关，机器人有AI聊天接入，可以响应所有消息，为了防止群聊中发一句回一句，具体响应你消息的概率=`好感度/200 * 当前会话回复率`，
  当前会话回复率在群聊中默认为0.05，私聊时为1.0。
- 不论在什么情况下，触发违禁词均会扣掉好感度，不管你有没有启用违禁词插件。
- 与机器人对话可以增加好感度，而且增加的很快。

###### 好感度分级

| 好感度  | 级   |
|------|-----|
| 0    | 1   |
| 15   | 2   |
| 40   | 3   |
| 70   | 4   |
| 100  | 5   |
| 150  | 6   |
| 200  | 7   |
| 400  | 8   |
| 700  | 9   |
| 1000 | 10  |

##### 硬币系统

- 内置插件的天气，查询地点，点歌等均需要花费硬币。
- 目前硬币暂时无法获得，后期会更新抽奖签到功能获得。