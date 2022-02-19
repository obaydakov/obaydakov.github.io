---
title: How to Build a Knowledge Graph with Neo4J and Transformers
author: Oleg Baydakov
date: '2021-12-04'
slug: []
categories:
  - machine-learning
tags:
  - nlp
  - graphs
description: ''
thumbnail: '/post/2021-12-04-how-to-build-a-knowledge-graph-with-neo4j-and-transformers/images/image.jpg'
---

How to build a knowledge graph from job descriptions using fine-tuned transformer-based Named Entity Recognition (NER) and spacy’s relation extraction models. The method described here can be used in any different field such as biomedical, finance, healthcare, etc.

Below are the steps we are going to take:

* Load our fine-tuned transformer NER and spacy relation extraction model in google colab

* Create a Neo4j Sandbox and add our entities and relations

* Query our graph to find the highest job match to a target resume, find the three most popular skills and highest skills co-occurrence

[Link](https://www.kdnuggets.com/2021/11/build-knowledge-graph-neo4j-transformers.html)