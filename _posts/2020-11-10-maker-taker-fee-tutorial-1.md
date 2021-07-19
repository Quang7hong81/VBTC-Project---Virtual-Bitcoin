---
layout: post
title:   Maker / Taker Fee (Tutorial 1)
date:   2020-11-10 10:48:00 +0700
---
## Maker / Taker Fee (Tutorial 1)

Currently* Maker and Taker trading fees on VBTC are at the following levels:

> Maker Fee: 0,00%
Taker Fee: 0,25%

#### If you are not familiar with the terms maker and taker fee, then read on:

A **maker fee (0,00%)** is applied when you *provide* liquidity to the order book rather than *taking* it.
This is the case when you create an order which does NOT (when you are buying) match any existing ask orders (“lifting the ask”) or when you are selling matches any existing bid orders (“hitting the bid”).

A **taker fee (0,25%)** is applied when you *take* liquidity out of the order book rather than *providing* it.
This is the case when you create an order which will (when you are buying) match any existing ask orders (“lifting the ask”) or when you are selling will match any existing bid orders (“hitting the bid”).

#### In pictures:

In the screenshot below any buy order below 355,999,900VND/BTC and any sell order above 354,000,000 VND will hit the order book as “maker order” (and requires somebody else to fill your order).

![](https://blog.vbtc.exchange/assets/posts/2020-11-10-maker-taker-fee-tutorial-1/maker-taker-fee-screenshot.png)

In the screenshot above any buy order at or above 355,999,900VND/BTC and any sell order at or below 354,000,000 VND will hit the order book as “taker order” (and be instantly filled).

#### Further considerations:

While a maker order is generally “cheaper” in terms of fees, it has a different type of cost: 

While taker orders generally fill instantly since you are taking existing bids/ask orders out of the order book, with a maker order you must wait until somebody is selling/buying at the price specified by you.

This can at times result in the market prices moving away from your initial order and thereby ultimately end up more costly than an instant taker order.

What order type is the right one for you depends on your time preference / urgency to get your order filled as well as your general trading strategy.

*10.11.2020 - the trading fees on VBTC have remain unchanged for the past several years.*
