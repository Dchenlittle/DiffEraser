# DiffEraser: Generalized Text Erasure Based on Latent Diffusion Prior
First, the conventional Variational Auto-Encoder (VAE) encoder is replaced with a Diffusion-Prior (DP) encoder, through which the heterogeneous information from the LDM prior knowledge in latent space is integrated with the multi-level encoded features of the input image.
Second, a Latent-Fusion (LF) decoder is introduced, by which the heterogeneous features from both the LDM and DP encoders are integrated to generate high-quality text-erased results.



![image](https://github.com/Dchenlittle/DiffEraser/blob/main/Fig33_01.png)

## Todo List

## Environment

conda create -n differaser python=3.8 -y

conda activate differaser

cd differaser

pip install -r requirements.txt

## Datasets
### 1. Text Removal Dataset
#### __· NPID295__

## Copyright
This repository can only be used for non-commercial research purpose.
