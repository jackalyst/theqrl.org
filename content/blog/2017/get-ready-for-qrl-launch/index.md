---
layout: blog-post
slug: get-ready-for-qrl-launch
date: 2017-12-30
author: "Peter Waterland"
title: "Get ready for QRL launch!"
featured_image: 1B-4FApWgOHxBSXdPfXcthw.png
images:
  - 1B-4FApWgOHxBSXdPfXcthw.png
  - 1SiK2tlSC04GyBtFU7WRbSA.png
  - 1DqJBp49kqznMkq6jpvS0Ow.png
  - 1ksnAIIWdRgkKUtzNkjQrVA.png
  - 1SmXlYTW4gap6Oq9e5FeheA.png
forks:
  - actinium
---

What a year in the crypto ecosystem! I tend to try and ignore prices and concentrate on the project but it has been impossible to miss that the entire crypto ecosystem has grown to nearly 0.6 trillion dollars this year. Quite incredible for those of us who have been in the scene since 2012/3 patiently waiting for the world to see what we first noticed all those years ago. Such innovation and growth in the space is awe-inspiring. Crypto as an asset class and internet payment layer has well and truly arrived.

This is a long post so lets get through the big stuff first — the timing and details of the launch!

## Roadmap changes — mainnet launch mid Q1 2018

To launch as soon as possible we have made some major changes to our roadmap.

Those who know the project intimately are aware we have been diligently iterating our Proof-of-Stake protocol for several months on our public testnet.

We have made great progress, but our plan to launch on low power devices (Pi 3 and above) with our current protocol is proving challenging and has repeatedly pushed back our mainnet release in recent weeks.

We need to make some modifications to our protocol, further test these extensively and open it to peer review. This will take at least another 4–6 months to complete properly to enterprise level.

Security is everything for the QRL. We are using PQ-recommended *XMSS* to secure our accounts and transactions. We cannot compromise our launch with an immature POS protocol given how much value our project currently carries — and more importantly how much value it will hold in the future.

It is also vital we do not delay our launch further as prospective partners wishing to integrate with the QRL require a working chain and it is important we launch as #1.

With this in mind we made a big decision earlier this month to launch sooner with a temporary proof-of-work(POW) algorithm — cryptonight, used on monero/XMR, and hard fork to POS in Q3 2018.

Proof-of-work is battle-tested in the wild since 2009 and is massively simpler to integrate. **We have already fully adapted qrlcore to POW in our private developer testnet and aim to launch in mid Q1 2018 with an internal countdown already started**. Feature freeze has occurred already. We are preparing for external audit.

## Token migration

Token migration allowing users to move their ERC20 token balance to a burn address and be automatically included in mainnet launch **will open next month**. A blog post explaining the process in detail is on the way shortly after the New year. Users who don’t migrate in time for our mainnet launch window will, of course, still have the option later to unlock their coins safely.

Discussions with exchanges are ongoing — we are not at liberty to reveal anything new at this time!

## Proof-of-stake transition

Through 2018 we will maintain three QRL networks :

1. Mainnet-POW.
1. Testnet-POW.
1. Testnet-POS.

Full-time development and protocol testing will continue (and in fact expand) through 2018. As part of our regular hard fork schedule we will hard fork to pure POS in Q3 2018.

QRL emission schedules remain unchanged with 2399544.94 QRL (3.54% of available supply, 2.18% of total supply) expected to be mined prior to the transition to POS and staking.

## Ephemeral messaging

Our blockchain overlay messaging layer is now integrated into the codebase — utilising reference *Dilithium* and *Kyber* implementations. We now have three different post-quantum secure cryptographic systems built into the QRL.

This allows much of our exciting layer two functionality to now come online!

## Team expansion continues into 2018

We will shortly be announcing **three new full-time members of the team** working in UX, mobile and an additional core developer. More on this in the coming days. The QRL remote office is becoming a busy place to reside.

Additionally we are delighted to add** another advisor**, to the team. He is a founder of the [Counterparty project](https://counterparty.io) and has already proved an excellent addition to our growing project.

## Conferences 2018

{{< image "./images/1B-4FApWgOHxBSXdPfXcthw.png" >}}

{{< image "./images/1SiK2tlSC04GyBtFU7WRbSA.png" >}}

{{< image "./images/1DqJBp49kqznMkq6jpvS0Ow.png" >}}

{{< image "./images/1ksnAIIWdRgkKUtzNkjQrVA.png" >}}

Our QRL team is scattered across the globe — from the UK, US and Canada, to the Netherlands, India and Australia.

We will be venturing outdoors and attending the following conferences to raise the profile of our project publicly in the first half of 2018 — [BlockDelhi](https://www.blackarrowconferences.com/blockdelhi.html), [APAC Australia](http://www.apacblockchain.com.au/), [CryptoValley](https://www.cryptovalleyconference.com/) and the[ Blockchain Global Expo](https://blockchain-expo.com/global/). We also plan on potentially adding more conferences to the first half of 2018 (i.e. Consensus 2018), with more to come in the second half of 2018!

I hope we can meet many of you at these events and spread the word of our project far and wide. Look out for the blue/purple QRL logo t-shirts!

## Mainnet launch featureset

We will ship with the following featureset in Q1 2018.

1. multi-platform qrlcore node release.
1. 100% PQ-secure address space for the QRL (*XMSS*)
1. cryptonight POW algorithm, 1 minute block-time interval, ability to mine in existing pools, using existing mining software.
1. ephemeral messaging layer capability (PQ-secure end-end data channel functionality utilising *Kyber* and *Dilithium*).
1. completely separated wallet and node functionality with all wallet-based requests passing through the node by our universal grpc api.
1. Use of slave XMSS tree signing capability to allow secure mining (and later in the year staking) keeping private keys offline.
1. GUI-based webwallet and full block explorer functionality
1. PQ-token capability out of the box — creating tokens on the QRL chain is now functional.
1. PQ-secure data stamping functionality out of the box.

In addition we are working very hard to implement full *XMSS *signing* *on the Ledger Nano, and expect a prototype WhatsApp-style PQ-secure messaging app to be available around the time of mainnet launch to show off early Ephemeral capabilities.

## TLDR

1. QRL goes live mid Q1 2018 with a transition from POW to POS via hardfork Q3 2018.
1. ERC20 to QRL Token Migration commences next month.
1. Team grows with several new members on the way and a new advisor

**Countdown to a fully post-quantum secure blockchain has begun.**

**Happy New Year to everyone from the QRL team: Adam, Aidan, Andrew, Burke, Elliott, Jack, JP, Juan, Kaushal, Leon, Michael, Scott and myself!**

{{< image "./images/1SmXlYTW4gap6Oq9e5FeheA.png" >}}