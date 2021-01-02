---
layout: post
title: "2020_4th_quarter"
date: 2020-10-08
image_url: https://user-images.githubusercontent.com/32321592/98316905-a7b9a000-201e-11eb-8135-053b5662ff85.png
mathjax: true
comments: true
---

# Unsupervised Cross-Modal Alignment of Speech and Text Embedding Spaces
## Yu-An Chung, Wei-Hung Weng, Schrasing Tong, James Glass
### 발표자: 강진구 [[paper link](https://arxiv.org/pdf/1805.07467.pdf), [presentation material](https://trello-attachments.s3.amazonaws.com/5d15b7297b29f54b88064f86/5f02bdd4b0d4f0561a33f47e/d3d19109ef206fd6ea1c4537529531ce/Unsupervised_Cross-Modal_Alignment_of_Speech_and_Text_Embedding_Spaces.pdf)]
- 음성에서 직접 word embedding을 추출하는 speech2vec의 후속 논문입니다.
- speech2vec에서는 음성을 forced alignment라는 방법으로 text와의 align을 맞추어서 그 alignment에 따라 단어들의 구간을 구분하고 구분된 단어 음성들을 가지고 skipgrams와 cbow 방법을 이용하여 word embedding을 추출합니다. 그런데 forced alignment는 음성에 해당하는 텍스트를 필요로 하는 방법이기 때문에 fully unsupervised라고 볼 수 없습니다.
- 본 논문에서는 여러 clustering algorithm (BES-GMM, Embedded segmental K-means, Recurring syllable-unit segmenter) 를 이용하여 speech2vec을 fully unsupervised 하게 발전 시켰습니다.
- 음성을 텍스트처럼 의미단위로 discrete하게 만들어 보려고 시도하는 참신한 연구라고 생각합니다.
<p align="center">
<img src="https://user-images.githubusercontent.com/25892000/92999642-8deb6780-f55d-11ea-8acc-2c483433f588.png">
</p>

***
