---
layout: post
section-type: post
title: Machine Learning experience
category: University
tags: [ 'Machine Learning', 'Python', '2017' ]
---

Two of Imperial's greatest highlights for me have been the flexibility over the courses you take and the vast amount of practical work you get to do. During this 3rd year we have been able to choose all of our modules. A new introduction to machine learning course was started this year, which I ventured to do and found it asinteresting as challenging. 

Throughout the course we have not only learned the fundamental theory behind machine learning but have also applied it in a variety of scenarios. The result was 4 extensive reports solving problems through a mix of maths and programing. <!--break-->

The programing was open and implementations varied, but the importance was placed on the analysis of the results. I personally chose python because of its versatility, quick developement process and the available machine learning libraries, such as [Scikit-learn](http://scikit-learn.org). 

All the code and the reports can be found in this Github [repository](https://github.com/jeg114/machine_learning). 

## Digit Classification Case Study

```
if(!machine_learning){
   goto take-away;  #First and only time I used this
}
```

One of my favourite aspects of this course was the observed progression throughout the course. During our first assignment, which had the perceptron algorithm as our emphasis we did a simple classifier of hand written digits. These classifier was trained with the perceptron algorithm to separate digits 2 and 8 based on a provided data set. This data set contained 2 dimensional data points which were obtained by a simple function mapping a 255 dimensional point to 2 dimensions. The results were not incredible: a training error of _24%_ and a test error of _44%_. A graph of this classifier can be observed in this.

[Perceptron Digit Classifier](/img/digits1.png)

There was margin of improvement since the same algorithm running on the full 255 dimensional data set (which unlike the 2D set was lineraly separable) brought the errors to _0%_ and _0.49%_ respectively. After somonths of working through the course, we revisited this classification with a deeper understanding. This time the classifier was trained using a RBF kernel based Support Vector Machine. Moreover instead of the simple functions to obtaine the 2D set, a 2D set was obtained using Principal Component Analysis. This reslted in a substantially better trainer with only _0.89%_ test error which can be observed in the screenshot from report 4 below.

![SVM Digit Classifier](/img/digits2.png)

**Take-away**:

## Contents
* Report 1:
  * Hoeffding's inequality
  * Perceptron algorithm
  * Hand written digit classification
* Report 2:
  * Empirical Risk Minimization
  * Bounds using VC dimensions
  * Structural Risk Minimization
* Report 3:
  * Epsilon optimal hypothesis
  * Cross Validation
  * Movie ratings' prediction (Netflix Challenge)
* Report 4:
  * Tykhonov regularization
  * Maximum margin linear Separator
  * Suport Vector Machines
  * Revised Digit Classification with SVM and PCA





