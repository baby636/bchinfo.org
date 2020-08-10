---
## This file is licensed under the MIT License (MIT) available on
## http://opensource.org/licenses/MIT.

title: "November 2020 Network Upgrade"
shorturl: "nov-upgrade"
active: true
banner: "The Bitcoin Cash network is upgrading (click here to read)"
bannerclass: "info"
date: 2020-08-09
---

## Summary

The Bitcoin Cash network will be undergoing an upgrade on November 15th, 2020. This upgrade will set a new difficulty adjustment
algorithm for the protocol. This algorithm, [aserti3-2d](https://read.cash/@jtoomim/bch-upgrade-proposal-use-asert-as-the-new-daa-1d875696), will bring more stable block times to the network.

## Reasons for the New Algorithm

The current difficulty adjustment algorithm on the Bitcoin Cash network has an exploit which allows miners to game the difficulty for profit.
The result of this gaming is wildly varying block times, ranging from a few seconds to several hours, and damage to the user experience of 
Bitcoin Cash. This new algorithm aims to solve these issues, and restore the 10 minute per block average.

## The Upgrade Plan

The network will upgrade when the Median Time Past (MTP) of the past 11 blocks is greater than or equal to unix timestamp of 1605441600, or Sunday, November 15, 2020 12:00:00 UTC.
To be compatible with the network upgrade, please see the recommended software below.

## Software with the Network Upgrade

The following node versions are recommended to be up-to-date and in-line with the November protocol upgrade. Not running these versions, or any version after, might result in
your client or server following the wrong chain.

* Bitcoin Cash Node: TBA
* Bitcoin Unlimited: TBA
* BCHD: TBA
* Flowee The Hub: TBA
* Bitcoin Verde: TBA
* Knuth: TBA
* Bitcoin ABC: TBA

