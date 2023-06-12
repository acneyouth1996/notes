---
layout: post
title: An incomplete guide to probability theory
date: 07-06-2023 16:27:43 :z
tags: [stats]
description:
summary:
comments: false
author: Yong Huang
mathjax: true
render_with_liquid: true
---

This is a brief introduction/cheatsheet to probability theory. Most of the content is from the book "Statistical Inference" [^fn1]


## 1.Basics
I assume you have some basic ideas of set theory such as what is intersection and what is union.

### 1.1 $$\sigma$$-algebra and measure theory
You probably don't need to know this. But in case you need it, here is the definition of $$\sigma$$-algebra. 

A collection of subsets $$\mathcal{S}$$ is called **sigma algebra**, denoted by $$\mathcal{B}$$, if it satisfies the follwoing three conditions:


1.   $$\emptyset \in \mathcal{B}$$ (the empty set is an element of $$\mathcal{B}$$)
2.   If $$\mathcal{A} \in \mathcal{B}$$, then $$\mathcal{A}^{c} \in \mathcal{B}$$
3.   If $$\mathcal{A}_{1}, \mathcal{A}_{2},... \in \mathcal{B}$$, then $$\cup_{i=1}^{\infty} \mathcal{A}_{i} \in \mathcal{B}$$ 


### 1.2 Rules of probability

The definition of probability function:

Given a sample space $$\mathcal{S}$$ and an associated sigma algebra $$\mathcal{B}$$, a probability function satisfies:

1.   $$\mathcal{P}(\mathcal{A})  \geq 0$$ for all $$\mathcal{A} \in \mathcal{B}$$.
2.   $$\mathcal{P}(\mathcal{S}) = 1$$.
3.   If $$ \mathcal{A}_{1}, \mathcal{A}_{2}, ... \in \mathcal{B}$$ are pairwise disjoint, then $$ \mathcal{P}(\cup_{i=1}^{\infty} \mathcal{A}_{i}) = \sum_{i=1}^{\infty} \mathcal{P}(A_{i})$$.

Some calculus of probability:

If $$\mathcal{P}$$ is a probabilty function and $$\mathcal{A}$$ is any set in $$\mathcal{B}$$, then

1.  $$ \mathcal{P}(\emptyset) = 0$$.
2.  $$ \mathcal{P}(A) \leq 1$$.
3.  $$ \mathcal{P}(\mathcal{A^{c}}) = 1 - \mathcal{P}(\mathcal{A})$$.
4.  $$ \mathcal{P} (\mathcal{A} \cup \mathcal{B}) = \mathcal{P}(\mathcal{A}) + \mathcal{P}(\mathcal{B}) - \mathcal{P} (\mathcal{A} \cap \mathcal{B})$$.
5.  $$ \mathcal{P} (\mathcal{B} \cap \mathcal{A}^{c}) = \mathcal{P}(\mathcal{B}) - \mathcal{P} (\mathcal{A} \cap \mathcal{B}) $$. 
6.  If $$\mathcal{A} \subseteq \mathcal{B}$$, then $$\mathcal{P}(\mathcal{A}) \leq \mathcal{P}(\mathcal{B})$$.


ordered list test

1. 1st item
2. 2nd item
    1. 1st sub-item of 2nd item
    2. 2nd sub-item of 2nd item
3. 3rd item
    1. 1st sub-item of 3rd item
    2. 2nd sub-item of 3rd item

blablabla 




### 1.3 Independence


### 1.4 Random variables

### 1.5 Distribution functions

### 1.6 Densities

## 2. Transformation and Expectation

## 3. Common family of distribution

## 4. Joint, marginal, and conditional distributions

## 5. Convergence in probability
You probably don't need to know too much details about this.

[^fn1]: Casella, G., & Berger, R. L. (2021). Statistical inference. Cengage Learning.
