# *Generating Classification Weights with GNN Denoising Autoencoders for Few-Shot Learning*

The current project page provides [pytorch](http://pytorch.org/) code that implements the following CVPR2019 paper (accepted as oral):   
**Title:**      "Generating Classification Weights with GNN Denoising Autoencoders for Few-Shot Learning"    
**Authors:**     Spyros Gidaris, Nikos Komodakis    
**Code:**        https://github.com/gidariss/wDAE_GNN_FewShot    

**Abstract:**  
Given an initial recognition model already trained on a set of base classes, the goal of this work is to develop a meta-model for few-shot learning. The meta-model, given as input some novel classes with few training examples per class, must properly adapt the existing recognition model into a new model that can correctly classify in a unified way both the novel and the base classes. To accomplish this goal it must learn to output the appropriate classification weight vectors for those two types of classes. To build our meta-model we make use of two main innovations: we propose the use of a Denoising Autoencoder network (DAE) that (during training) takes as input a set of classification weights corrupted with Gaussian noise and learns to reconstruct the target-discriminative classification weights. In this case, the injected noise on the classification weights serves the role of regularizing the weight generating meta-model. Furthermore, in order to capture the co-dependencies between different classes in a given task instance of our meta-model, we propose to implement the DAE model as a Graph Neural Network (GNN). In order to verify the efficacy of our approach, we extensively evaluate it on ImageNet based few-shot benchmarks and we report strong results that surpass prior approaches.


# CODE COMING SOON
