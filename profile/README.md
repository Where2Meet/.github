# Where2Meet

在美国, 到一个人生地不熟的地方, 难免会感到孤独, 当自己想要跳出生活圈的时候, 难免发现比想象中困难.

类似于小红书, 我们想提升用户的生活体验. 不同于小红书, 我们更多是为了提升用户之间的参与度, 为他们提供一条可以交结更多朋友的渠道. 很多人在小红书找活动伴子, 但是由于小红书信息太杂, 信息过多, 又或者比如积目, 为了交朋友但是又不一定志同道合. 我们会提供不同的板块, 用于通过不同的活动来结交更多的朋友.

for starter, 从一个活动开始 - skiiing

## Skiing

找朋友滑雪不容易, 但是我们会滑雪主题的平台, 精确到每个城市, 这样可以在搜索的途中更加便捷有效 (California -> Lake Tahoe -> Heavenly -> Green Line -> Find your mate)

- Geographic search: 根据用户要搜索的位置, 显示范围内的所有雪场
- Best Match: 每个雪场有不同的滑道, 对应了平台内的多个 channel, 用户可以发送自己的‘房间’来等待, 或者寻找匹配的‘房间’
- Where: App 会提供用户之间的实时位置查询 以及 group chat, 保证有效沟通 + 防止诈骗

# 总结

- 这个产品包含了小红书 (多人发帖), 积目 (位置搜索), 群聊 (QQ), Zenly (实时位置分享)
- 这里给人们找搭子提供了更好的服务, 并且是以人为本, 支持人们线下交流, 这只是一个‘招生’软件, 要想让客户持续使用我们的软件, 后续会增加新的板块: 比如滑雪经验 & 技巧交流, 更偏向于帖子 & 博客的模式, 而且会增加评分系统, 让用户更好的分辨这个雪场是不是最好的选择

# 难点

- 数据库:
  - 保存用户聊天数据
  - 保存店铺地理位置
- 搜索:
  - 如果要一层一层的搜索, 这样过于繁琐, 要如何做好 search engine 是一大难点

## Repositories

### Client Apps

| Platform  | Repo                                                                  | Status | Releases |
| --------- | --------------------------------------------------------------------- | ------ | -------- |
| Web (PWA) | [Where2Meet-spa](https://github.com/Where2Meet/WhereToMeet-spa)       | -      | -        |
| Mobile    | [Where2Meet-mobile](https://github.com/Where2Meet/WhereToMeet-mobile) | -      | -        |

### Database Platform

| Repository                                                                                                                 | 🚀 Release Pipeline | ⚒️ Debug Pipeline |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------- | ----------------- |
| [WhereToMeet](https://github.com/Where2Meet/Where2Meet) <br /> _(Super-repo containing all repos below as Git submodules)_ |                     |                   |
| [Where2Meet.DataStore.Abstractions](https://github.com/Where2Meet/Where2Meet.DataStore.Abstraction)                        |                     |                   |
| [Where2Meet.DataStore.MongoDB](https://github.com/Where2Meet/Where2Meet.DataStore.MongoDB)                                 |                     |                   |
| [Where2Meet.DataStore.Redis](https://github.com/Where2Meet/Where2Meet.DataStore.Redis)                                     |                     |                   |
| [Where2Meet.DataStore.DataManager](https://github.com/Where2Meet/Where2Meet.DataStore.DataManager)                         |                     |                   |
| [Where2Meet.Search.Abstraction](https://github.com/Where2Meet/Where2Meet.Search.Abstraction)                               |                     |                   |
| [Where2Meet.WebAPI](https://github.com/Where2Meet/Where2Meet.WebAPI)                                                       |                     |                   |

### Docker & Kubernetes (K8s)

| Repository | Pipelines |
| ---------- | --------- |
|            |           |
|            |           |
|            |           |
|            |           |
