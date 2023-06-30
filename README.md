浪子之心科技lil
ImageTalking-Wav2Lip-CodeFormer
此代码仅为演示输入一张图片，然后动作迁移将图片模仿成视频，再用wav2lip进行语言驱动嘴型，最后用CodeFormer进行高清化的过程。
效果比sadtalker好。
此方案本人再3月份已经开源到B站视频，现在将代码一起开源。
步骤一：输入一张图片，用DaGAN，DPE，Thin-Plate-Spline-Motion-Model，first-order-model，StyleHEAT等动作迁移算法将图片迁移成视频。
步骤二：输入音频，用wav2lip或者video-retalking,DInet等数字人驱动算法将迁移后的视频驱动成说话的视频。
步骤三：用CodeFormer，GFPGAN，PGEN等进行后期超分修复。

Lavender Heart Technology lil
ImageTalking Wav2Lip CodeFormer
This code is only used to demonstrate the input of an image, followed by action transfer to imitate the image into a video, followed by language driven mouth shaping using wav2lip, and finally, the high-definition process using CodeFormer.
The effect is better than Sadtalker.
I have already opened up this solution to Bilibili Video in March, and now I will open up the code together.
Step 1: Enter an image and use action transfer algorithms such as DaGAN, DPE, Thin Plate Spline Motion Model, first order model, and StyleHEAT to transfer the image into a video.
Step 2: Input audio and use digital human driver algorithms such as wav2lip or video retailing, DInet, etc. to drive the migrated video into a speaking video.
Step 3: Use CodeFormer, GFPGAN, PGEN, etc. for post segmentation repair.
## Inference  
### Please click on the Colab link below to inference.
[![Open In Colab][colab-badge]][colab-notebook]
[colab-notebook]: <https://colab.research.google.com/github.com/langzizhixin/lil/blob/main/lil.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
***

## Useful links:
https://github.com/sczhou/CodeFormer
https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model
https://github.com/Rudrabha/Wav2Lip
### 
### 

***

### Project lil made by Lu Rui from Langzizhixin Technology company in Chengdu, China.
###  Code 2023
