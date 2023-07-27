---
title: 'An Overview of Artificial Intelligence Accelerators'
date: 2022-12-15
permalink: /posts/2022/06/csatpaper/
excerpt: '<mark style="background-color: #b4e7fa">Tech Post</mark> From Algorithms to AI Accelerators: Unraveling the Evolution of Computer Hardware in the Age of Artificial Intelligence. Term paper written for Computer System Architecture class - CSCI 6461.'
tags:
  - Artificial Intelligence
  - Accelerators
  - Computer Architecture
---
> This blogpost showcases the introduction section of a term paper I wrote for a graduate level computer architecture course. The full article can be found [here](/files/ChadhaH Term Paper CSCI6461Section12Spring2022November262022.pdf){:target="_blank"}

Artificial Intelligence is that branch of computer science that deals with the development of computer systems that emulate cognitive behavior to simulate complex abilities such as perception of vision, recognition of speech, logical deduction, reasoning, etc. The scientific work that can now be recognized as the earliest example of the demonstration of artificial intelligence fundamentals is the McCulloh and Pitts (1943) artificial neuron that characterized a formal turing complete design. Today, this technology is ubiquitous and intimately intertwined with the human experience. The salient ideas of artificial intelligence and associated fields have been here for more than 50 years. But despite the obvious utility of this technology their use only become prominent in everyday life in the past decade.

This latency can be attributed, in part, to the lack of computer infrastructure equipped to deal with the massive amount of processing power required by artificial neural networks to generate useful results. Thus, while algorithmic innovations were at the center of the AI revolution, one of the most important contributors to the success of the field was the improvements in the underlying architecture capable of performing the required calculations, given algorithmic constraints. For instance, it is a widely held belief that the research work titled Alexnet as presented by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton (2017) from the University of Toronto rang in a new era for the AI community. They utilized a specialized hardware unit - the GPU to compute the neural network more time efficiently. While their algorithm itself was not revolutionary, their creation of an innovative mapping of the convolution operations set their solution apart.

Hence, without the ability to learn complex data relations in a reasonable time frame - a capability imparted because of the improvement in the way the networks are computed - we would perhaps not have seen such widespread adoption of AI techniques, useful as they may be.

Changing the way in which an AI algorithm is implemented makes the algorithm run more efficiently and saves time especially when it comes to massive real-life computations. An example of this can be demonstrated by taking the case of matrix multiplication - a ubiquitous operation in AI. In Figure 1 we see how using different computation methods to perform this operation can help improve processor performance.

<img src='/images/csatermp.png'>

This is where AI accelerators come into play. An artificial intelligence accelerator may be defined as a high-efficiency computing device that is capable of handling large-scale neural network workloads due to its specialized design and parallel processing capabilities. These are specialized hardware units present in computer systems that help speed up AI operations by virtue of the highly specific nature of their architecture.

They are a special category of hardware accelerators - processors that are designed to increase the efficiency of the CPU by taking away some of the specialized task load. This helps in increasing the performance of the computer and the efficiency with which the task is executed. Hardware accelerators combine the flexibility that is afforded by the presence of general-purpose CPUs with the performance efficiency that specialized hardware offers to optimize task performance. A few examples of processors being used as AI accelerators are GPU or graphical processing units that are most adept at dealing with parallelized processing of massive amounts of data. Other devices include FPGAs or field programmable gate arrays and ASICs or application-specific integrated circuits.

In this article, a comprehensive survey of the field of artificial intelligence accelerators has been undertaken. The first section highlights the pivotal role these specialized processors have played in the progress of the field of artificial intelligence. Following this, the evolution of computer processors and the advancements that brought about the need for the development of accelerators has been traced. Further, a detailed discussion of the major categories of AI accelerators has been conducted. The last two sections of the article present a detailed overview of the various leading industry processors that are driving innovations in the field of AI and summarise the general industry trends prevalent.
