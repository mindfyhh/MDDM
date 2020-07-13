# Code for "Multi-scale Dynamic Feature Encoding Network for Image Demoireing" [ICCV2019 AIM Workshop][[arxiv]](https://arxiv.org/abs/1909.11947)
**MDDM is the 2nd place winner of AIM Demoireing Challenge-Fidelity**

**[Update] An enhance version: MDDM+ will be uploaded**

**Team: MoePhoto**
**Team Members: Xi Cheng, Zhenyong Fu, Jian Yang**

## Requirement:
 1. GPU>= 11GB Memory
(We have tested on RTX2080Ti/Titan V/Tesla P40)
 2. Python 3.6.6
 3. Pytorch==1.2.0
 4. torchvision==0.4.0a0+6b959ee
 5. scikit-image==0.13.1

## Test the model:
    Put the images in ./data/TestingMoire 
    Run  (Fidelity) 
    python test_all.py --cuda --model ./models/mddm.pth 
    Run  (Perceptual)
    python test_all.py --cuda --model ./models/mddmgan.pth

## Train:
[WIP]
