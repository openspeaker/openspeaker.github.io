---
layout: project
title: WIFI SPEAKER STARTER KIT
comments: true
---

<div class="message">
  This page was written in Chinese
</div>

--------

<div class="message">
  做一款足够便宜的WIFI AUDIO好底板
</div>

--------

## WHY

* 发现网络上还蛮不少朋友在业余时间玩基于7688的WIFI SPEAKER系统,但是各个朋友的底板往往不同

* 普遍使用的 WM8960 声音确实不好

* 本站的第一个方案(WM8741)物料成本太贵，与 WM8741 搭配的必须周边零件也很贵...

--------

## GOAL

* 兼容 linkit smart 7688 和 mango 家的小核心板
* 依然追求相对好的声音，较好的 SNR，192K audio，低抖动MCLK，CS4344 DAC
* 底板除了Audio以外引出必要的功能（网口，USB，TF CARD，TTY-UART）
* 便宜/容易获得(PCB 售价 RMB 9；所有物料均可通过淘宝购买，提供链接)
* 开源(将公开原理图，PCB，GERBER，当然还有软件github)

--------

## DELIVERABLES

1. PCB - 光板 (售价 RMB 9)
2. KIT - 光板 + 关键零件 (售价 零件淘宝价钱 x2 + RMB 9 ==> 估计 RMB 39元 )  [以下补充说明1]
3. PCBA - 焊接好可以直接使用的的底板 (售价 KIT + RMB 50 ==> 估计 RMB 89 元)  [以下补充说明2]
4. 数量。计划 PCB total 30 PCS, KIT total 30 PCS, PCBA 5 PCS  [以下补充说明3]

* _以上不含邮费_

```
说明 1：关键零件不包括贴片 R，C （封装为0603的普通零件）
说明 2：只是兴趣目的，没有做钢网和打件的计划(玩耍但不能花太多钱)，鼓励大家自己动手焊接，实在不想焊可以找群友互相帮助。
说明 3：博主我焊接水平有限，也没有很多时间，我打算焊5PCS，5PCS以后还有群友需要则我需要收 RMB 100 的手焊费用。勿喷，我真心鼓励大家 DIY
```

--------

## SOLDING 

* 对于有烙铁的群友焊接网口和USB HOST应该没有难度
* 有尖头烙铁、焊台的群友应该也能焊0603的贴片器件
* 焊接 mini USB 和小 IC 可能会难一些
* 对于新手，焊接教程请在youku搜索
* 目的是让更对群友玩 wifi audio，我鼓励有时间的群友自行采购物料，小批量焊接转卖给有兴趣的群友

--------

## SCHEDULE

* 打算 6月的第一周周末画板子 --> should be delay
* 6月的第二周周末焊接和调试 --> should be delay

--------

## ORDERING

订购请加 Widora QQ 群，发信息给 Widora 群友 '大力'

订购名单

| QQ          |  DESC        |     QTY     |  TOTAL    |
| :---        | :---         | :---        |  :---:    |
| xxxx        |  PCB         | 5           |  45       |
| xxxx        |  KIT         | 1           |  39       |
| xxxx        |  PCBA        | 1           |  89       |

--------

## INFORMATION

如果你只关心linkit smart，需要网口和USB，并且不需要 audio。那么可以购买邻家这个 --> [Smart 7688 扩展板 底板](https://item.taobao.com/item.htm?id=528313226881)


### updated

```
5/26 当天在 QQ 群发起过投票，继续讨论请用下面的 Disqus。
对板子需要的请发 Q 我，发 mail 我。大概统计好数量在画板子。目标专著于小功放方案。
```