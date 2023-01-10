---
title: 'Future Blog Post'
date: 2023-01-01
permalink: /posts/2023/01/blog-post-3/
tags:
  - cool posts
  - category1
  - category2
---
Working these weeks with Ersilia has been a great learning experience, I have had to face problems installing python packages and installing machine learning modules in the Conda environment, problems with the “python path” variables, even having to read one and again scientific literature until trying to understand concepts about chemistry. All the problems that I have been facing would not have been solved if I had not FIGHTED to find a solution. 
And it is that persevering and persisting is the key to finding the solution to many conflicts when we work. This is a key point for learning and this is where growth occurs for whatever we are doing. 

Within Ersilia's tasks I was working on the incorporation of new AI models for Ersilia, in this case we are based on other models already developed in the python language and that are of interest to Ersilia and of high priority. 
In the first model that was assigned to me was to predict metabolites of small molecules in humans, really something totally new for me would become a great challenge, to apply my knowledge and to be able to make a real contribution to Ersilia. Now I want to teach you all the new concepts I learned while embedding this model. 

First, it is very important to read the scientific literature and understand the purpose of the model to be incorporated, the machine learning tools that were used to train the model, understand the methodology with which the author approached the problem, and the technological tools used, version of python and dependencies to install for this to work in a Conda environment with Ersilia on my local system. 
Some important concepts I learned in this process: What are metabolites? and Why is it so important for research to address this topic? .
Metabolites are the substance that is produced in the body during a metabolic process. It is the substance that the body makes or uses when it breaks down food, or drugs. 
Xenobiotics are compounds not found naturally in the body such as drugs, pesticides, and pollutants. During the metabolic process, there are certain enzymes involved in the elimination of these xenobiotics. In the case of drugs, this elimination process can lead to a reduction in the efficacy of the drug and pose safety problems, since we could have metabolites that are toxic. for the body and in some very serious cases, this could lead to liver problems. Because of all this, I have a really important problem to address and a great help to science. That is why the study of metabolites is a very important part of drug development, and for Ersilia it becomes a high priority. 

METABOLITES PREDICTION PROBLEM TREATED AS A TRANSLATION PROBLEM USING DEEP LEARNING NEURAL MACHINE TRANSLATOR. 

Ersilia uses ML tools for drug discovery, which makes drug development studies faster. Unlike the studies that are traditionally done, and in the case of drug metabolism, requires a lot of time and effort, and manual work by experts. And in the case of the problem of predicting metabolites, there is great difficulty in obtaining the structures of the metabolites. That is why in this model, they approach the problem of metabolite prediction as a problem of translation of sequences of chemical compounds of SMILES notation. To manage this metabolite prediction problem, the author uses “transfer learning” in a deep learning transformative model, trained on chemical reactions to predict the outcome of metabolic reactions. This molecular transformation model is inspired by language translation, using the openNMT toolkit. It also builds an ensemble model to account for multiple and diverse metabolites. This allows a more complete study of different types of enzymes and enzymes from more common families, which cannot be obtained in other traditional models. Making this study better than other models.
 Here is a graphical representation: 
Adding a model to Ersilia was difficult. Despite having the literature to study the metabolite prediction problem, there were new machine learning concepts in this implementation, I had to consult the internet for concepts such as "learning by transfer", and research about the openNMT toolkit. All this is in order to be clear about the operation of the model and to be able to address problems that arise. 
Thanks to the organization in the processes that Ersilia has and to all the documentation that they provide us, the guide to incorporate models was of great help, and mentoring with the community. Step by step I was incorporating the model into the Ersilia model Hub. Now thanks to this collaborative work with the community, Ersilia has one more model in her backend.







This post will show up by default. To disable scheduling of future posts, edit `config.yml` and set `future: false`. 
