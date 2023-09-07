---
title: 'Locally Stationary Graph Processes'
date: 2023-08-28
permalink: /posts/local-stationary
tags:
  - lsgp
  - publications
  - about
---

In today's data-driven world, accurately modeling and understanding the relationships between different data points is crucial. This blog post introduces a new approach, known as Locally Stationary Graph Processes (LSGP), which takes graph theory to the next level by allowing more nuanced models of data relationships. But what exactly are graph processes, and how do they relate to data? Let's dive in.

Think of a graph as a network where each point (or vertex) represents an individual data point and the lines (or edges) represent relationships between them. In traditional graph modeling methods like Wide Sense Stationary Graph Processes (WSS), we assume that each point in the network behaves similarly. In other words, the influence of neighboring points on any given point is consistent throughout the graph. Imagine a classroom where every student learns from the teacher in the exact same way, regardless of their individual learning styles or friendships.

But what if that's not the case? What if, in that same classroom, one student learns better from their friends, while another student learns more effectively from the teacher? This is where LSGP comes in. Unlike WSS, LSGP allows for local variations in the behavior of data points. It recognizes that each point in the network might have unique relationships with its neighbors, much like each student in the classroom has a unique learning experience.

So, if you've ever wondered why one-size-fits-all models don't always fit all, stay tuned. We'll explore how LSGP can provide a more accurate and nuanced understanding of complex data relationships.

LSGP equation is given by 
$$
x = \sum_{i = 1}^K \mathbf{G}_k \mathbf{U}_{\mathcal{G}} h_k(\mathbf{\Lambda}_{\mathcal{G}}) \mathbf{U}_{\mathcal{G}}^T \mathbf{w}
$$