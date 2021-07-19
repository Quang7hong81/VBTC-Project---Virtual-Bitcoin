---
layout: post
title:   Batched SegWit Withdrawals (Tutorial 5)
date:   2021-01-17 20:55:00 +0700
---
Congratulations! You bought your first Bitcoin on VBTC and are now looking to withdraw your Bitcoin from the platform.

But hold up, what is that… 0.001 BTC withdrawal fees for onchain transactions?

If you only bought a small amount of Bitcoin and are mostly looking to transfer it to other Bitcoin users or services, you might instead consider using the [Lightning Network](https://blog.vbtc.exchange/2020/how-to-withdraw-bitcoin-lightning-network-tutorial-3) for your withdrawals.

However - if you are looking to receive your Bitcoin on-chain and are not in a hurry you can now use the “Batched SegWit” withdrawal option to significantly save on 80% on withdrawal fees [currently at 0,0002 BTC per withdrawal].

VBTC will process these queued withdrawals in manual fashion at every weekend in order to optimize [for the transaction fees paid](http://mempool.space).

In this article we are going to explain to you how you can save 80% of the withdrawal costs via our new “Low Urgency - Batched SegWit” withdrawal option.

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image1.jpg)

#### Not in a rush? Chose Batched SegWit withdrawals!

If you do not have the urgency to receive your Bitcoins within the next block mined (approx. 10 minutes) in your own wallet, you can now choose the batched SegWit withdrawal options.

While Instant withdrawals are submitted as a single transaction to the Bitcoin Network the moment you confirm your withdrawal with a high fee to receive a fast confirmation - a batched SegWit withdrawal is looking to optimize for the amount of transaction fees required.

VBTC is able to offer this solution due to:
- Batching several withdrawals into one single transaction
- Timing the submission of the transaction with a low transaction backlog in the [Mempool](http://mempool.space)
- Utilization of more efficient address scheme [[bc1… - also known as “Native SegWit address’](https://en.bitcoin.it/wiki/Invoice_address)]

Currently the batched SegWit withdrawals are processed on a weekly basis at each weekend.

The cut-off time to be included for certain in the weekly batch settlement is each **Friday, 6 PM Vietnam time zone**.
 
#### What to do to receive a SegWit withdrawal?

First of all, you need a SegWit-enabled wallet and provide VBTC upon submitting your withdrawal request with a valid native SegWit address (“bc1…” address, for more information you can read the Bitcoin Wiki entry on [Bech32](https://en.bitcoin.it/wiki/Bech32 "Bech32")*).

On VBTC, go to “Withdrawals” and click “Withdraw Bitcoin”.

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image3.jpg)

Choose option “Bitcoin (Low Urgency for reduced tx fees - Weekly settlement via Batched Segwit)”

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image1.jpg)

Enter the amount of Bitcoin you are looking to withdraw and copy your Native SegWit address into the corresponding field.*

![](/assets/posts/2021-01-17-batched-segwit-withdrawals-tutorial-5/image2.jpg)

And that’s it!

Since withdrawals are processed manually by our team due to security reasons, the withdrawals are not instant but will generally arrive in your wallet each weekend during the processing of the accumulated Batched SegWit withdrawals for our VBTC clients.
 
**Non-bc1… addresses will be charged an additional 0.00005 BTC withdrawal fee since they are not using the most block-space efficient transaction formatting.* 

---

*If you want to learn more about Bitcoin transaction processing, mempool usage and the “fee market” and are based in Vietnam, we also strongly recommend joining the regular [local Bitcoin meetups in Saigon](http://bitcoinsaigon.org/) where a variety of entrepreneurs are building various services with & on the Bitcoin Network.*
