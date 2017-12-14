+++
abstract = "We consider the problem of non-parametric Conditional Independence testing (CI testing) for continuous random variables. Given i.i.d samples from the joint distribution f(x,y,z) of continuous random vectors X,Y and Z, we determine whether X⊥Y|Z. We approach this by converting the conditional independence test into a classification problem. This allows us to harness very powerful classifiers like gradient-boosted trees and deep neural networks. These models can handle complex probability distributions and allow us to perform significantly better compared to the prior state of the art, for high-dimensional CI testing. The main technical challenge in the classification problem is the need for samples from the conditional product distribution fCI(x,y,z)=f(x|z)f(y|z)f(z) -- the joint distribution if and only if X⊥Y|Z. -- when given access only to i.i.d. samples from the true joint distribution f(x,y,z). To tackle this problem we propose a novel nearest neighbor bootstrap procedure and theoretically show that our generated samples are indeed close to fCI in terms of total variational distance. We then develop theoretical results regarding the generalization bounds for classification for our problem, which translate into error bounds for CI testing. We provide a novel analysis of Rademacher type classification bounds in the presence of non-i.i.d near-independent samples. We empirically validate the performance of our algorithm on simulated and real datasets and show performance gains over previous methods."
authors = ["Rajat Sen", "Ananda Theertha Suresh", "Karthikeyan Shanmugam", "Alex Dimakis", "Sanjay Shakkottai"]
date = "2017-12-03"
image = ""
image_preview = ""
math = true
publication = "Accepted in NIPS 2017"
title = "Model-Powered Conditional Independence Test"
url_code = "https://github.com/rajatsen91/CCIT.git"
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1709.06138"
url_project = ""
url_slides = "/pdf/CIposter.pdf"
url_video = "https://www.youtube.com/watch?v=w6-yib0JUOk"
+++

