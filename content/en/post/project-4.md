---
date: 2021-04-19T11:14:48-04:00
description: "Reinforcement Learning with convolutional neural networks"
featured_image: "/images/alvaro-serrano-hjwKMkehBco-unsplash.jpg"
tags: ["transfer learning", "convolutional neural network", "digits", "letters", "handwritten", "image recognition"]
title: "Recognizing Handwritten Letters with Neural Networks"
---
The goal of this project was to create a convolutional neural network (CNN) model that can recognize handwriting from the first five letters in the alphabet (A,B,C,D,E).  We had to use transfer learning in order to create a model that can do that.  Transfer learning is when a machine learning model that is trained to solve one problem is applied to solve a different but related problem.  In this scenario we used a CNN that was trained to recognize handwritten digits and applied it to recognizing handwritten letters. The data for the handwritten letters were obtained by friends and family.


{{< figure src="/images/0002.jpg">}}
     "Example of Handwritten Letter Training Data"

{{< figure src="/images/letterAcc.jpg">}}
      "Loss and Accuracy Charts of CNN Model"

[Github Repository](https://github.com/MrinmoyBhaumik/handwrittenletters)
