---
layout: post
title: The First Blocker
---

## TAS5731 does not work

Work very hard with fun in two days, handmade a TAS5731 board, also debug with TAS5731 EV board, final found the TAS5731 can not work with MT7688

* MT7688 cannot output MCLK for TAS5731
* even TAS5731 can work with MCLK from SCLK(64FS)
* BUT MT7688 only support 32FS SCLK
* SO... cannot easily setup the TAS5731+MT7688 (might need extra PLL for the MCLK)


Give up this solution and try others

1. TAS5731 cannot do very good sound
2. Extra PLL will cost a lot (if good PLL, I do not know details indeed, but I don't want to spend time on it for now)

### My handmade board
![w600](/images/2016_0120_top_tas5731.jpg)

### bottom view
![w600](/images/2016_0120_bottom_tas5731.jpg)

### waveform looks not that bad..
![w600](/images/2016_0202_i2s_waveform.jpg)


