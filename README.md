# DiffEraser: Generalized Text Erasure Based on Latent Diffusion Prior

This is the official PyTorch codes for the paper.

![image](https://github.com/Dchenlittle/DiffEraser/blob/main/Fig33_01.png)

## Todo List
* Download link for the non-sensitive portion of NPID295

* Generation Code for the NPID295 Dataset

* Training Code

* Testing Code

* DiffEraser Model Code
## Environment

* conda create -n differaser python=3.8 -y

* conda activate differaser

* cd differaser

* pip install -r requirements.txt

## Datasets
### NPID295

The NPID295 dataset is a synthetic dataset consisting of 4,877 images, with 3,377 images used for training and 1,500 images used for testing. The synthetic text in NPID295 has arbitrary fonts, colors, positions, and sizes. It provides two types of annotations: text removal images (b) and text mask images (c). The dataset is divided into non-sensitive and sensitive portions. The non-sensitive portion is from open-access datasets and can be shared(https://pan.baidu.com/s/1kpuseadCcqgoB-qLmle8XA(pwd:4321)). The sensitive portion, sourced from copyrighted web content, is subject to restrictions. To provide full dataset access, we provide a direct download link for the non-sensitive portion and offer synthesis code for the sensitive portion. The synthesis process includes text mask extraction, content randomization (size and position), and background augmentation (cropping, photometric enhancement, and noise addition).

![image](https://github.com/Dchenlittle/DiffEraser/blob/main/dataset.png)

Note: Similar to SCUT_EnsTex, the NPID295 dataset can only be used for non-commercial research purposes.

## Contact

If you have any questions, feel free to concat us or raise issues.

Suggestions and opinions of our work (both positive and negative) are welcome. 

## Copyright
This repository can only be used for non-commercial research purpose.
