# cs152_final_project
ViT evaluation over CIFAR-10 dataset

## Important Links

* [Our Code](https://github.com/f-wright/ViT-implementation/tree/d7c5d79dc8656cc55ae0ce606a4aefad32eaa22e)
* [Our Writeup](https://hwalters361.github.io/cs152_final_project/)
* [Our Presentation](https://youtu.be/jW1Box9xh9U)

## Abstract

Our project explores the capabilities of using transformers for image classification problems. We use the model for a Vision Transformer (ViT) as detailed in the paper An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale and compare its performance against other ViT architectures, then examine it when the value of hyperparameters is varied. We found that Simple ViT continued to perform better than ViT, even on small datasets. With regards to the hybrid architecture, we found that the Simple-ViT model had the most success. We observed that low patch sizes and low number of heads in the attention layer stop the ViT from training. And as expected the convolutional neural network performed the best given our limited computational resources.
