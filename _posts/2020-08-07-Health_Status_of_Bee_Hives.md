---
title: "Health Status of Bee Hives"
date: 2020-08-07
tags: [data science life circle, data science, EDA, Pandas , NumPy , Matplotlib , Seaborn , sklearn, CNN, GCP]
header:
  image: "https://scx1.b-cdn.net/csz/news/800/2017/honeybees.jpg"
  teaser: "https://scx1.b-cdn.net/csz/news/800/2017/honeybees.jpg"
excerpt: "Data Science Life Circle, Data Science, Neural Networks for Good"
mathjax: "true"
---

# Introduction

The use of neocorticoids and other pesticides against insects is a growing problem because they are targeting not only the target insects which can act as pests but also useful ones like honey bees. There is a rapid decrease in the number of insects. Also it was shown before that insecticides can reduce the defense strength of the bee hives against the [varroa mites](https://www.nature.com/articles/s41598-019-44207-1). Without these insects the agriculture will lose a major contributor to the pollination of plants, which can lead to crop failures and famines.
I want to predict the health status of bee hives based on a [kaggle dataset](https://www.kaggle.com/jenny18/honey-bee-annotated-images) that contains 5,100+ bee images annotated with location, date, time, subspecies, health condition, caste, and pollen. 
The first steps will be getting an overview about the dataset and how the different annotations of the pictures are distributed, then I want to build a basic classification models using supervised or unsupervised machine learning and then improve the prediction if possible with CNN and improving it. The final goal it will be to use GCP and Google Vision. The major challenges of this data set will be the different sizes and quality of the bee images and the testing of the model on bee hive livestreams.
The success of this project will be defined by the accuracy of the detection of the health status of bee hives in the real world and the usability for primary stakeholders like beekeepers. 




