---
# Course title, summary, and position.
linktitle: Communication complexity 2018
summary: 15 lectures, each of 90-minutes duration.
weight: 2

# Page metadata.
title: Communication complexity
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Communication complexity
    weight: 1
---

## Preamble

The area of communication complexity studies measures communication as computational resource---a mathematical abstraction that encompasses all the problems with communication bottleneck. The basic model of communication complexity deals with two parties, namely Alice and Bob. Their task is to compute a function on input which is distributed among them. For doing so, they communicate between each other adhering to a set of rules which they agree upon a priori, and what we measure is the number of bits they need to communicate in order to compute the function. This problem, and many of its variants, appear frequently in practice in many guises and in different levels of abstractions---in network protocols where the goal is to minimize the communication (and thereby error in communication) between two network hubs, in VLSI circuit design where the goal is to minimize energy used and to pack efficiently by decreasing the amount of wires required, also in data-structure, circuit complexity, auctions and a plethora of other interesting areas of study.

In this course, we will discuss the classical results in communication complexity and also cover the recent developments and important open problems. We will discuss different models of communication complexity---deterministic, nondeterministic, asymmetric, randomized, and multiparty---and their inter-relationship. We will mostly be interested in showing combinatorial, algebraic and information theoretic techniques for showing communication complexity lower bounds, i.e., for showing that certain functions cannot be computed without a lot of communication no matter how clever the communication algorithm is.

## 📢 News

* Lectures are over! My (hand-written) lecture notes are available [here](https://drive.google.com/file/d/12_nnnhrz2vJAQ2mK-mMV-IuTLu57mASh/view).
* We will have two lectures by Jakob Nordström on June 11 and 13.
* [Homework 3](https://drive.google.com/file/d/1R3buaDJtC0iyHcKty7tsxhN_SoPTWBAA/view) has been posted. Due date: May 30.
* [Homework 2](https://drive.google.com/file/d/12J2X_hnxAxkeMDtP1xwSF70oBS3AfMT2/view) has been posted. Due date: May 16.
* [Homework 1](https://drive.google.com/file/d/1EbUWayBicdfIKwib_yxOGFtQSJI-l6ZN/view) has been posted. Due date: May 9.
* 1 lecture per week during week 16 - 17.
* 2 lectures per week during week 18 - 25.