![Pbot](https://socialify.git.ci/Pzzzzz5142/Pbot/image?description=1&font=Source%20Code%20Pro&language=1&logo=https%3A%2F%2Fraw.githubusercontent.com%2FPzzzzz5142%2FPbot%2Fmaster%2FPbot%2Favatar.JPG&owner=1&pattern=Signal&stargazers=1&theme=Light)

# Pbot

一个相对不那么xjb写的，并基于Nonebot2的QQ🤖。

功能很杂，代码风格很要命。

## 功能概览

+ **搜图**：包括以图搜图及关键字搜图。
+ **机器翻译**
+ **点歌**
+ **戳一戳**
+ **切噜一下**：（抄自[Hoshino](https://github.com/Ice-Cirno/HoshinoBot)
+ **根据 P 站 id 看原图**
+ **复读**
+ **每日早上好**
+ **今日人品**
+ **能不能好好说话**

## RoadMap

| 版本   | 发布时间或 Milestone 截至时间            | Key Feature             |
| ------ | ---------------------------------------- | ----------------------- |
| v0.1.0 | 2020-11-24                               | 老Bot的关键功能迁移完成 |
| v0.2.0 | 咕                                       | 老Bot的全部功能迁移完成 |
| v0.3.0 | 估                                       | 配置方式优化            |
| v0.4.0 | 沽                                       | 可迁移部署及文档完善    |
| ？     | 咕咕咕                                   | 没想好                  |
| ---    | （可能永远无法完成（真的不大可能有（（（ | web UI                  |

## 功能

### st

搜图的缩写（不然你以为是什么的缩写）

**触发条件**：消息以`st`开头

**后续参数**：

+ 图片信息：使用[SauceNao](https://saucenao.com)搜索图片来源，并返回结果。
+ 文字信息：使用[Pixivic](https://pixivic.com)搜索图片。

### wm

当你面对洋文、太君文、ру́сский язы́к等手足无措时，宁是否觉得自己像是个文盲一样呢？没关系，wm（文盲）功能将会解决宁的烦恼！

**触发条件**：消息以`wm`开头，空格后接你要翻译的文字。

**参数**：

+ 可选
    + --fr 或 -f 文本源语言
    + --to 或 -t 文本目标语言

其中，源语言及目标语言如下表：

| 语言简写 | 名称         |
| -------- | ------------ |
| auto     | 自动检测     |
| zh       | 中文         |
| en       | 英语         |
| yue      | 粤语         |
| wyw      | 文言文       |
| jp       | 日语         |
| kor      | 韩语         |
| fra      | 法语         |
| spa      | 西班牙语     |
| th       | 泰语         |
| ara      | 阿拉伯语     |
| ru       | 俄语         |
| pt       | 葡萄牙语     |
| de       | 德语         |
| it       | 意大利语     |
| el       | 希腊语       |
| nl       | 荷兰语       |
| pl       | 波兰语       |
| bul      | 保加利亚语   |
| est      | 爱沙尼亚语   |
| dan      | 丹麦语       |
| fin      | 芬兰语       |
| cs       | 捷克语       |
| rom      | 罗马尼亚语   |
| slo      | 斯洛文尼亚语 |
| swe      | 瑞典语       |
| hu       | 匈牙利语     |
| cht      | 繁体中文     |
| vie      | 越南语       |

### 点歌

**触发条件**：消息以`点歌`开头

**参数**：你要点的歌

> 剩下的介绍还在 Working 中。可以先看[这里](https://github.com/Pzzzzz5142/xjbx-QQ-group-bot)了解相关功能！（毕竟正在迁移到 Nonebot2 ）

## 安装

Working 中

## 配置

Working 中