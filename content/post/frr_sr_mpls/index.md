---
title: "FRRoutingでSR MPLSを動かす"
date: 2018-10-16T15:57:19+09:00
draft: true
toc: false
comments: false
categories:
- 研究
- 技術メモ
tags:
- Segment Routing
- SR MPLS
---

[FRRouting](https://github.com/FRRouting/frr "FRRouting")に実装されているOSPFのSR拡張と，Linux Kernel 4.3.0より実装されているMPLS機能を用いてSegment Routingを動作させます．  
[ospf-srのドキュメント](https://github.com/FRRouting/frr/blob/master/doc/developer/ospf-sr.rst "ospf-sr")のSupported Featuresの通り，OSPFによるSID（ラベル）配布を確認した後，iproute2を用いてMPLSのスタティックルートを設定します．

[設定手順はこちら](https://qiita.com/watal "FRRoutingでSR MPLSを動かす")

<!--more-->
