# Generative Adversarial Networks (GAN) Application Case Study through MNIST Dataset
### 1. The Objective and Ideas:

To explore more advanced areas in deep learning after the course works, I selected Generative Adversarial Networks and it’s variants, which are becoming the most important algorithm pattern in Deep Learning. MNIST Dataset’s simplicity on implementation makes it the great fit for learning the GAN concept.


### 2. Outline

#### Generative Adversarial Networks (GAN)
* Background
* Architecture
* Application Areas and Examples  

#### A Case Study using MNIST Image Dataset 
* Introduce MNIST Dataset through a classification example
* Case Study: Generate MNIST images through GAN

### 3. Generative Adversarial Networks (GAN) Review

### 3.1 GAN Snapshoot

<img width="813" alt="gan_snapshoot" src="https://user-images.githubusercontent.com/18288611/51065246-79f1a480-15c9-11e9-9afd-27f5eb8fb627.png">

### 3.2 GAN Architecture

<img width="675" alt="gan_architecture" src="https://user-images.githubusercontent.com/18288611/51066168-4cf3c080-15ce-11e9-9902-297b6b17a529.png">

#### GAN Architecture (MNIST as an example)

<img width="740" alt="gan_instance" src="https://user-images.githubusercontent.com/18288611/51065266-968ddc80-15c9-11e9-975b-40bc63012bd2.png">

### 3.3 GAN Applications example

<img width="818" alt="gan_applications" src="https://user-images.githubusercontent.com/18288611/51066242-b542a200-15ce-11e9-9e7b-391f42cb39ae.png">

#### Industry Use Case: Drug Discovery vs. Drug Design (Generate)

<img width="794" alt="grug_discovery" src="https://user-images.githubusercontent.com/18288611/51066777-f8eadb00-15d1-11e9-8e80-3bcf5501f333.png">

#### Industry Use Case Solution: ChemGAN on Drug Discovery

<img width="797" alt="chemgan" src="https://user-images.githubusercontent.com/18288611/51066786-1e77e480-15d2-11e9-81c8-a55019f3a039.png">

### 4. A GAN Case Study using MNIST Image Dataset 

### 4.1. Experience MNIST 

#### MNIST Dataset

<img width="634" alt="mnist_dataset" src="https://user-images.githubusercontent.com/18288611/51065964-46187e00-15cd-11e9-9b44-8281da466de3.png">

#### MNIST Data Example
<img width="775" alt="mnist_data" src="https://user-images.githubusercontent.com/18288611/51065983-5c263e80-15cd-11e9-8d98-c57b08f414ad.png">

#### A results of loss/accuracy vs. epocdes diagram of the simple Feed forward Neural Network
<img width="614" alt="mnist_result_analysis" src="https://user-images.githubusercontent.com/18288611/51066572-a52bc200-15d0-11e9-8139-f124c6bef046.png">

### 4.2. Experience GAN with MNIST

#### Put together Generator and Discriminator to GAN Model
<img width="813" alt="gan_networks" src="https://user-images.githubusercontent.com/18288611/51066370-592c4d80-15cf-11e9-8b3e-28bbe175d47f.png">

#### Apply the GAN Model to get the generated images based on parameters (i.e. epocdes)
<img width="815" alt="gan_model_app" src="https://user-images.githubusercontent.com/18288611/51066433-b922f400-15cf-11e9-8fa1-c5f569ffde4d.png">

#### GAN Results Review
<img width="823" alt="gan_results" src="https://user-images.githubusercontent.com/18288611/51066472-eff90a00-15cf-11e9-9a59-16550f57cc37.png">

The results show the image quality improved signficantly with the epcodes (iterations). The image quality of 400 epochs is close to the real MNIST Images.   

### 5. Reference

* https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf
* https://skymind.ai/wiki/generative-adversarial-network-gan
* https://github.com/llSourcell/AI_for_healthcare/blob/master/Healthcare%20Drug%20Discovery.ipynb





