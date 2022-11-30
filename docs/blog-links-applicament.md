---
title: 友链申请
sidebar_position: 4
---

# 站点友链申请

> P.S. 目前该申请只对 Galaxy City 开放。

## 优先条件

或许大家都知道 **友链友链，先友后链** 这句话吧？虽然我很想交一些新朋友而不强求先友后链，但对于老朋友当然是有效的。

嗯，就这样。如果是属于银河眼熟的人都可以无视下面的大部分规则、顺利交换友链哒~~~///(^v^)\\\~~~

## 基础要求

- 站点内容：
  - 文章多为原创，可少量转载；
  - 没有过于敏感，比如摄政（懂的都懂）、颜色、无脑地域黑等等；
- 博客类型：独立博客，不是 CSDN、新浪博客这种类型的；
- 域名：要求为独立域名（支持二级域名），亦或是带有身份特征的免费域名
  - 独立域名泛指 restent.win / restent.cf 这样的、由本人持有的域名；
  - 带有身份特征的免费域名泛指 restent.js.org 这样的、由本人完全控制的免费二级域名；
  - 不支持的域名类似 114514.coding-pages.com 或 restent.github.io/blog（即免费域名 + 二级目录）。

## 如何交换

首先，将本站信息添加到你的友链列表里（排名先后无所谓）；

:::note Galaxy City 的友链信息

站点名：Galaxy City

站长名：Restent Ou / SliverRiver （前英文名后 ID）

Slogan：光阴流转前行，永无停歇之时

链接：<https://blog.restent.win>

Favicon：<https://img.restent.win/me/profile/favicon.png>
:::

添加完成之后，你有两种方法交换友链：

### 自助添加

前往 [SliverRiver-Network/Friends](https://github.com/SliverRiver-Network/Friends) 并编辑 `linklist.json`：

```json
{
    "nickname": "SliverRiver",
    "avatar": "https://img.restent.win/me/profile/avatar.jpg",
    "site": "https://blog.restent.win"
}
```

上述是一个示例。其对应的意思是：

- nickname -> 名称（个人）

- avatar -> 头像（链接）

- site -> 站点（链接）

添加完成后请提起一个 PR，我在看到之后会审核并合并。

### 邮件提醒

请将你的名称、头像链接、站点链接发至 [i@restent.win](mailto:i@restent.win)。

我在看到之后将会手动添加至 json 列表。
