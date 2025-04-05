# VIE-DM
This repository contains the data and code for the following paper:\
  Jingcheng Ke, Jun-Cheng Chen, I-Hong Jhuo, Chia-Wen Lin, Yen-Yu Lin, Generation and Comprehension Hand-in-Hand: Vision-guided Expression Diffusion for Boosting Referring Expression Generation and Comprehension. In ICLR2025.

Installation\
Install the dependency packages from the projects QRNet and DiffuSeq

Preparation\
Download the checkpoints of DiffuSeq and swin transformer and put them into the folder pre_train_models

dataset\
1. Download the data of 'RefCOCO' and put them into the floder datasets/folder. The link of 'RefCOCO' is 'https://drive.google.com/drive/folders/15E10sR0KEL1N5rYOtBYpAtVlWs-uOlRE?usp=sharing'
2. Download the images of 'COCO' and put the 'train2014' to the folder datasets/folder

Training\
cd scripts\
bash train.sh

Decoding\
cd scripts\
bash run_decode.sh
