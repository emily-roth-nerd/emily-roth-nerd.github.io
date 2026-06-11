---
title: 'Blog Post number 4'
date: 2015-08-14
permalink: /posts/2012/08/blog-post-4/
tags:
  - cool posts
  - category1
  - category2
---


* Introduction

Imagine that you a college administrator and you earnestly want to know about the drug use of the student population. A very practical research question is how should you solict responses? This is a tricky problem because students are incentivized to lie. There are real consequences to being identified as saying yes. Even if the survey is a google form that is supposed to be anynomous, many students will under-report their drug use. 

The solution that no particular student can be proven to use drugs regardless of how they respond. Furthermore, the data in aggregregate at least still needs to be useful administrators as data. Consider the following set of instructions. 

1. Students are told to privately flip a fair coin.
2. If it comes up heads, then they answer honestly. 
3. But if it comes up tails, then they flip the coin again and answer Yes if heads and tails if no. 

The appeal of this scheme is that any student can claim afterwards they answered heads because of the sequence of coin flips. Although we introduced noise, there is still data the college can work with. What is the probabality a student answers yes given they have done drugs. It is $\frac{1}{2} + \frac{1}{4}= \frac{3}{4}$. Meanwhile the probabality that they answer yes given they have not done drugs is $\frac{1}{4}$. Therefore if a portion of the students, $p$, actually use drugs then the the college would get an aggreate response of $\frac{3p+(1-p)}{4} n$. If they recieved $X$ yes answers then their estimate of $p$ would be $2 \frac{X}{n} - \frac{1}{2} $. 