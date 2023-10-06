---
permalink: /
title: ""
excerpt: ""
author_profile: true


---
Projects
======

Segment Your Ring (SYR)
------
Using Segment Anything Model (SAM) released by Meta, the objective is to segment rings used in product packshots. The challenging part is that SAM doesn't perform well with rings on a white background. Therefore, I adpated SAM with LoRA to solve this task.


![image](https://raw.githubusercontent.com/MathieuNlp/Sam_LoRA/main/docs/images/best_model_on_test.png)

[![](https://img.shields.io/badge/Segment%20Anything-maker?color=white)](#)
[![](https://img.shields.io/badge/-Pytorch-white)](#)
[![](https://img.shields.io/badge/-LoRA-white)](#)
[![](https://img.shields.io/badge/-Gradio-white)](#)

[[Code]](https://github.com/MathieuNlp/Sam_LoRA/)

------

Inpainting with Stable Diffusion and Segment Anything
------
Stable diffusion and segment anything are two foundation models that were recently released. I combined stable diffusion inpainting model that requires an image and a mask with segment anything that generates masks (with prompts or automatically) to custom pictures. The project has a webui made with gradio.


![image](https://raw.githubusercontent.com/MathieuNlp/Sam_Stable/main/webui_screen.jpg)

[![](https://img.shields.io/badge/Stable%20Diffusion-maker?color=white)](#)
[![](https://img.shields.io/badge/Segment%20Anything-maker?color=white)](#)
[![](https://img.shields.io/badge/-Gradio-white)](#)
[![](https://img.shields.io/badge/-Pytorch-white)](#)

[[Code]](https://github.com/MathieuNlp/Sam_Stable/)

------

Cat face generator
------
GAN models are generative models that train a generator through a discriminator in a zero sum game. I tried to generate cats face with a DCGAN model.


![image](https://user-images.githubusercontent.com/78492189/244523427-2867d1b9-a1ee-47ed-9299-3f0f57b74c3b.png)


[![](https://img.shields.io/badge/-Python-white)](#)
[![](https://img.shields.io/badge/-Pytorch-white)](#)

[[Code]](https://github.com/MathieuNlp/cat_gen)

------

Tweet virality predictor
------
The popularity of a tweet can vary depending on the author, the audiance and other parameters. In this project, I built a full pipeline from getting tweets
to predict the virality of them with a Hawkes process fine-tuned by a RandomForest. Finally I deployed the system with Docker and Kubernetes.

[![](https://img.shields.io/badge/-Python-white)](#)
[![](https://img.shields.io/badge/-sklearn-white)](#)
[![](https://img.shields.io/badge/-C%2B%2B-white)](#)
[![](https://img.shields.io/badge/-Kafka-white)](#)
[![](https://img.shields.io/badge/-Docker-white)](#)
[![](https://img.shields.io/badge/-Kubernetes-white)](#)
[![](https://img.shields.io/badge/-Git-white)](#)

[[Code]](https://github.com/MathieuNlp/Tweetoscope)

------

Convex contouring obstacles on water with Kernel Density Estimation
------
This project calculate the convex contour of probability given a cloud of points.

[![](https://img.shields.io/badge/-Python-white)](#)
[![](https://img.shields.io/badge/-sklearn-white)](#)

[[Code]](https://github.com/MathieuNlp/DRP_KDE)

------

Evaluation of marine ecosystem through plankton species
------
Plankton are a good estimator of marine ecosystem. In the context of the <a href="https://anr.fr/fr/detail/call/challenge-ia-biodiv-recherche-en-intelligence-artificielle-dans-le-champ-de-la-biodiversite/"> Biodiversity AI Challenge</a>, I was asked to create a model that classify plankton species based on a highly unbalanced dataset.

[![](https://img.shields.io/badge/-Python-white)](#)
[![](https://img.shields.io/badge/-sklearn-white)](#)
[![](https://img.shields.io/badge/-Pytorch-white)](#)

[[Code]](https://github.com/MathieuNlp/Plankton-Classif)

------
