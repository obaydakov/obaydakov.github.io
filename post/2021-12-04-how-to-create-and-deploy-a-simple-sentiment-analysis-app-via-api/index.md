---
title: How to Create and Deploy a Simple Sentiment Analysis App via API
author: Oleg Baydakov
date: '2021-12-04'
slug: []
categories:
  - machine-learning
tags:
  - graphs
  - nlp
description: ''
thumbnail: '/post/2021-12-04-how-to-create-and-deploy-a-simple-sentiment-analysis-app-via-api/images/image.jpg'
---
FastAPI might be able to help. FastAPI is FastAPI is a web framework for building APIs with Python. We will use FastAPI in this article to build a REST API to service an NLP model which can be queried via GET request and can dole out responses to those queries.

For this example, we will skip the building of our own model, and instead leverage the Pipeline class of the HuggingFace Transformers library. Transformers is full of SOTA NLP models which can be used out of the box as-is, as well as fine-tuned for specific uses and high performance. The library's pipelines can be summed up as:

The pipelines are a great and easy way to use models for inference. These pipelines are objects that abstract most of the complex code from the library, offering a simple API dedicated to several tasks, including Named Entity Recognition, Masked Language Modeling, Sentiment Analysis, Feature Extraction and Question Answering.

Using the Transformers library, FastAPI, and astonishingly little code, we are going to create and deploy a very simple sentiment analysis app. We will also see how extending this same approach to a more complex app would be quite straightforward.

[Link](https://www.kdnuggets.com/2021/06/create-deploy-sentiment-analysis-app-api.html)