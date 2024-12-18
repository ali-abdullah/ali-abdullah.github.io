---
layout: post
title:  "Game Plan Overview"
date:   2017-06-28 5:38:00 -0400
categories: Machine Learning 
---
Contents

1. toc
{:toc}

## Personal intrests in AI ## 

Based on an Intel [article][intel-ai] the following are key concepts.

# First Things First—What Exactly is AI? #

While there are a lot of different ways to think about AI and a lot of different techniques to approach it, the key to machine intelligence is that it must be able to sense, reason, and act, then adapt based on experience.

* `Sense` — Identify and recognize meaningful objects or concepts in the midst of vast data. Is that a stoplight? Is it a tumor or normal tissue?
 
* `Reason` — Understand the larger context, and make a plan to achieve a goal. If the goal is to avoid a collision, the car must calculate the likelihood of a crash based on vehicle behaviors, proximity, speed, and road conditions.
 
* `Act` — Either recommend or directly initiate the best course of action. Based on vehicle and traffic analysis, it may brake, accelerate, or prepare safety mechanisms.
 
* `Adapt` — Finally, we must be able to adapt algorithms at each phase based on experience, retraining them to be ever more intelligent. Autonomous vehicle algorithms should be re-trained to recognize more blind spots, factor new variables into the context, and adjust actions based on previous incidents.


![AI TODAY](/images/AI-Circle.jpg){:class="img-responsive" height="500px" width="700px"}

 - - - -

# The Plan # 

Current game plan is to start with middle ground Machine Learning and statistical learning and then move above or below from there. 

That being said, I'm currently going through Andrew Ng's [Stanford course][Standford course]  
As well as some kaggle sets, to get some practical application in with scikit.

## Types of Machine Learning ## 

# Supervised #

The training data consist of labeled inputs and known outcomes, which the machine studies until it can apply the label on its own. For example, to create a face detection algorithm, you might provide images of landscapes, people, animals, buildings, and so on, with their respective labels until the machine could reliably recognize a face in an unlabeled image.

 

# Unsupervised #

The machine analyzes unlabeled data and categorizes it based on similarities it has identified. So, you might provide the same photos as in the above example, but without their labels. The machine would still be able to cluster images based on shared characteristics (the sharp lines of a cityscape vs. the round shape of a face, for example)—but it would not be able to say that that round shape is a “face.” These programs are used to identify groupings within data sets that may be difficult or impossible for a human to see.

 

# Semi-supervised #

A combination of the above, used when there is a large amount of data but only some of it is labeled. Unsupervised learning techniques might be used to group and cluster the unlabeled data, while supervised learning techniques can be used to predict labels for it.

 

# Reinforcement learning # 

Uses simple reward data to train the machine on ideal behavior within a specific context.

- - - -

## Order of approach for Machine Learning: ##

1. Supervised learning
	1. Supervised learning setup. LMS.
	2. Logistic regression. Perceptron. Exponential family. 
	3. Generative learning algorithms. Gaussian discriminant analysis. Naive Bayes. 
	4. Support vector machines. 
	5. Model selection and feature selection. 
	6. Ensemble methods: Bagging, boosting. 
	7. Evaluating and debugging learning algorithms. 
2. Learning theory
3. Unsupervised learning
4. Reinforcement learning and control

[intel-ai]:https://software.intel.com/en-us/articles/how-to-get-started-as-a-developer-in-ai 
[Standford course]:http://cs229.stanford.edu/
[Link]:#Supervised 