Project: Generative AI for Data augmentation in medical images (Course Project for IE 643)
Team: Vishnu
Team members: Moparthy Venkata Subrahmanya Sri Harsha (Roll: 24M2151), Ritesh Sur Chowdhury (Roll: 24M2154)

The codes for this task have been shared in IE643_Project_Codes.ipynb (with comments). 
The code consists of the dataloading and pre-processing, generation (VAE, DDPM) and segmentation (U-Net) models, training, performance metrics (FID Score, SSIM and SWD) and the interface.

We have uploaded two scripts: IE643_Projects_Codes.ipynb (which contains the codes executed duting Intensive Assessment) and IE643_Projects_Codes_Novelty.ipynb (where, we added the codes executed during novelty stage). We have also provided the interface code in both codes.
The details of the codes are written in the scripts.

Training and Inference details:
Learning rate: VAE: 0.001, DDPM: 5 × 10^(−5), U-Net: 0.001; Number of epochs: VAE: 700, DDPM: 1000, U-Net: 1000; Optimizer: Adam optimizer for all models; Training and Inference batch size: 16 for all models.

![image](https://github.com/user-attachments/assets/f95bb40d-93dd-481f-b712-ce1d9b5b4ef2)
