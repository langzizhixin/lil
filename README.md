Lavender Heart Technology "lil",
ImageTalking-Wav2Lip-CodeFormer,
This code is only used to demonstrate the input of an image, followed by action transfer to imitate the image into a video, followed by language driven mouth shaping using wav2lip, and finally, the high-definition process using CodeFormer.
The effect is better than Sadtalker.
I have already opened up this solution to Bilibili Video in March, and now I will open up the code together.
Step 1: Enter an image and use action transfer algorithms such as DaGAN, DPE, Thin Plate Spline Motion Model, first order model, and StyleHEAT to transfer the image into a video.
Step 2: Input audio and use digital human driver algorithms such as wav2lip or video retailing, DInet, etc. to drive the migrated video into a speaking video.
Step 3: Use CodeFormer, GFPGAN, PGEN, etc. for post segmentation repair.
***
## Inference  
### Please click on the Colab link below to inference.

[![Open In Colab][colab-badge]][colab-notebook]

[colab-notebook]: <https://colab.research.google.com/github/langzizhixin/lil/blob/main/lil.ipynb>

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

***

![input_image](input_image/100.jpg)
![input_image](input_image/8888.jpg)
![output-video](output/6301.mp4)

## Useful links:
https://github.com/sczhou/CodeFormer

https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model

https://github.com/Rudrabha/Wav2Lip
### 
### 

***

### Project lil made by Lu Rui from Langzizhixin Technology company in Chengdu, China.
###  Code 2023
