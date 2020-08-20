---
layout: post
title: "2020_3rd_quater2"
date: 2020-07-01
mathjax: true
comments: true
---

# Gate Decorator: Global Filter Pruning Method for Accelerating Deep Convolutional Neural Networks
## Zhonghui You, Kun Yan, Jinmian Ye, Meng Ma, Ping Wang, NeurIPS 2019
[paper link](https://arxiv.org/abs/1909.08174)
- Filter pruning 기법 중 하나로 기존 기법에 비해 효과적으로 filter의 importance를 정의하고, 이를 기반으로 filter를 제거 및 pruned network를 tuning할 수 있는 방법을 제안한 논문입니다.
- Gate decorator란 Taylor expansion에 기반한 기법으로, pruning할 각 layer에 gate vector를 추가 및 이의 gradient에 기반한 score를 정하며 이는 아래와 같습니다.

$$a^2 + b^2 = c^2$$
