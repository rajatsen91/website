+++
abstract = "Motivated by online recommendation and advertising systems, we consider a causal model for stochastic contextual bandits with a latent low-dimensional confounder. In our model, there are L observed contexts and K arms of the bandit. The observed context influences the reward obtained through a latent confounder variable with cardinality m (m ≪ L, K ). The arm choice and the latent confounder causally determines the reward while the observed context is correlated with the confounder. Under this model, the L × K mean reward matrix U (for each context in [L] and each arm in [K]) factorizes into non-negative factors A (L × m) and W (m × K). This insight enables us to propose an ε-greedy NMF-Bandit algorithm that designs a sequence of interventions (selecting specific arms), that achieves a balance between learning this low-dimensional structure and selecting the best arm to minimize regret. Our algorithm achieves a regret of O (Lpoly(m, log K) log T ) at time T , as compared to O(LK log T ) for conventional contextual bandits, assuming a constant gap between the best arm and the rest for each context. These guarantees are obtained under mild sufficiency conditions on the factors that are weaker versions of the well-known Statistical RIP condition. We further propose a class of generative models that satisfy our sufficient conditions, and derive a lower bound of O (Km log T ). These are the first regret guarantees for online matrix completion with bandit feedback, when the rank is greater than one. We further compare the performance of our algorithm with the state of the art, on synthetic and real world data-sets."
authors = ["Rajat Sen", "Karthikeyan Shanmugam", "Murat Kocaoglu", "Alex Dimakis", "Sanjay Shakkottai"]
date = "2017-04-22"
image = ""
image_preview = ""
math = true
publication = "Proceedings of the 20th International Conference on Artificial Intelligence and Statistics; pages: 518-527, volume = 54"
title = "Contextual Bandits with Latent Confounders: An NMF Approach"
url_code = ""
url_dataset = ""
url_pdf = "http://proceedings.mlr.press/v54/sen17a/sen17a.pdf"
url_project = ""
url_slides = ""
url_video = ""
+++

