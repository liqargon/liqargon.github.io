---
layout: page
title: Projects
permalink: /projects/
---

## FranChouChou Detector

<a class="h5 text-zombie-y"><i class="fab fa-github"></i>FranChouChouDetector</a>

![](/images/fccd1.jpg)

Twitter上で@zombie_LAr宛に画像リプを送ると画像リプを送ると画像からフランシュシュの顔を識別し、さくらちゃんが検出された場合は私のアイコンを更新するプログラム。

主要なライブラリは以下。
- OpenCV (顔認識)
- Pytorch (顔識別 CNN)

最近は動いてない。

## Zombie-Idol Converter (Name Pending)

<a class="h5 text-zombie-y"><i class="fab fa-github"></i>ZombieIdolConverter</a>

|![](/images/zic1.png)|![](/images/zic2.png)|
|---|---|
|![](/images/zic3.png)|![](/images/zic4.png)|

開発中。

ゾンビ状態のキャラをアイドル状態に。逆に、アイドル状態のキャラをゾンビ状態にするプログラム。
上は[CycleGAN](https://arxiv.org/abs/1703.10593)を用いたもの。
左が元の画像、右が変換後の画像。

いずれWebアプリとして公開予定(時期未定)。