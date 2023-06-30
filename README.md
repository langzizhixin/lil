浪子之心科技lil
ImageTalking-Wav2Lip-CodeFormer
此代码仅为演示输入一张图片，然后动作迁移将图片模仿成视频，再用wav2lip进行语言驱动嘴型，最后用CodeFormer进行高清化的过程。
效果比sadtalker好。
此方案本人再3月份已经开源到B站视频，现在将代码一起开源。
步骤一：输入一张图片，用DaGAN，DPE，Thin-Plate-Spline-Motion-Model，first-order-model，StyleHEAT等动作迁移算法将图片迁移成视频。
步骤二：输入音频，用wav2lip或者video-retalking,DInet等数字人驱动算法将迁移后的视频驱动成说话的视频。
步骤三：用CodeFormer，GFPGAN，PGEN等进行后期超分修复。
