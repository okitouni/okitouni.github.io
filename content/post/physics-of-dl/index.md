---
title: "The Physics of Deep Learning"
subtitle: "A lazy repository of what we understand about neural networks"
summary: "Our theoretical understanding of deep learning is still in its infancy. And as we figure out what questions to even ask, perhaps it would be useful to draw inspiration from the field responsible for some of the most successful theories in science. This is a lazy repository of what we know about deep learning."
authors:
- admin
tags: []
categories: []
date: "2023-06-21T00:00:00Z"
# lastMod: "2019-09-05T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Dall-E 3's interpretation of a the intersection of physics and deep learning"
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<!-- Change this color later -->
<!-- I don't want to write a long-winded introduction on how the study of the steam engine which started as an engineering discipline flourished into a theory of thermodynamics. Or how physics specializes in breaking down complex systems (just like neural networks) into their simplest components to derive theories that explain the emergent behavior of the system. I will just assume that you are already convinced that physics is a good place to look for inspiration.


With that said, this is will hopefully be a series of short blog posts that summarize some key ideas and concepts in our understanding of how deep learning works. I obviously will not claim that the material presented here will actually be *THE* physics approach to deep learning. In particular because many people will have many definitions for what that might be. So I will clarify the definition I will employ here. To me, a physics approach to deep learning is one that is inspired by the way physicists think about problems. This is not to say that the approach will be rigorous or even correct. All we aim to achieve here is an intuitive understanding of some key components of deep learning. This intuition should be able to generalize across different settings to a certain extent and further, it should be able to make some testable predictions. This approach is very pragmatic by its nature, but I plan on putting in additional effort to make sure *anyone* can follow along. For practitioner, this would translate to adding a new tool to guide intuition and for theorists, this would translate to a new way of thinking about the problem, and to everyone else, I hope you gain a new appreciation for common or foreign concepts in deep learning. 

Some topics I plan on talking about:
- Grokking, or generalization beyond overfitting.
- Lottery Ticket Hypothesis.
- Scaling Laws and infinite width limits.
- Topics in Mechanistic Interpretability.
- Miscellaneous topics in optimization via gradient descent in the Deep Learning setting. This includes things like the role of normalization, adaptive optimization, implicit/explicit regularization, etc. -->

 I don't want to write a long-winded introduction on how the study of the steam engine, which started as an engineering discipline, flourished into a theory of thermodynamics. Or how physics specializes in breaking down complex systems into their simplest components to derive theories that explain the emergent behavior of the system. I assume you are already convinced that physics is a good place to seek inspiration.


This will be a series of short blog posts summarizing a sample of ideas and concepts in our understanding of deep learning. I will not claim that the material presented here will be *THE* physics approach to deep learning, as that could mean many things to different people. My definition of a physics approach to deep learning is one that adopts physicist-style thinking. This is not to say that the approach will be rigorous or even *entirely* correct. All we aim to achieve here is an intuitive understanding of some key components of deep learning. This intuition should generalize across different settings to a certain extent and make predictions we can test empirically. This approach is very pragmatic by its nature, and I plan on expending additional effort to ensure *anyone* can follow along. For those in the trenches, this would translate to adding a new tool to guide intuition in designing, training, and deploying models, and to everyone else, I hope you gain a fresh perspective and a new appreciation for familiar (or foreign) concepts in deep learning. 

Some topics I plan on talking about:
- Grokking, or generalization beyond overfitting.
- Lottery Ticket Hypothesis.
- Scaling Laws and infinite width limits.
- Topics in Mechanistic Interpretability.
- Miscellaneous topics in optimization via gradient descent in the Deep Learning setting. This includes topics like the role of normalization, adaptive optimization, implicit/explicit regularization, etc.