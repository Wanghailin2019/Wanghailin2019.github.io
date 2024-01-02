---
title: '论文中Proposition和Corollary的区别是什么'
date: 2024-01-02
permalink: /posts/2024/01/2024-01-02-论文中Proposition和Corollary的区别是什么
tags:
  - mathematics
---

我们在看英文论文的时候，经常会看到定理-Theorem，以及propostion，corollary和lemma，我们往往统一翻译为引理，简单理解为由定理引出来的，小的定理。

那为什么英文要用三个不同的单词表达同一个意思呢，所以有理由怀疑这三个词表达的含义是有区别的。

首先，**Theorem** --> 定理，是论文或文章中最重要的数学化描述，一般有严格的数学证明；

**Proposition** --> 一般翻译为命题，是文中比较重要的结论，但是一般来说，没有Theorem那么的抽象和重要，比较常用。《Mathematics for Computer Sciences》
这本书中表示：Important propositions are called theorems.所以一般我们认为，theorem和propostion可以互换。

**Lemma** --> 一种比较小的定理，通常lemma的提出是为了来逐步辅助证明Theorem，有时候可以将Theorem拆分成多个小的Lemma来逐步证明，以使得证明的思路更加清晰。很少情况下Lemma会以其自身的形式存在。
《Mathematics for CS》：A **lemma** is a preliminary propostion useful for proving later propositions.

**Corollary** --> 推论，由Theorem推出来的结论，一般会说：this is a corollay of Theorem A. 《Mathematics of CS》: A **corollary** is a proposition that follows in just a few logical steps.

