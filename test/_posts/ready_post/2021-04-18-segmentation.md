---
title:  "segmentation"
excerpt: ""
categories:
  - 또다른정리
tags:
  - Object Detection
use_math: true
year-archive: 2021
last_modified_at: 2021-04-18T17:15:00-00:00
---

- Describe the conceptual design of fully convolutional neural networks and subsequent models based on it
- Describe the decoder section of the fully convolutional neural network
- Describe two methods of upsampling: simple scaling and transposed convolutions
- Build the encoder and decoder sections of a fully convolutional neural network
- Evaluate a segmentation model’s performance using intersection-over-union and Dice score
- Describe the conceptual design of the U-Net model
- Build a U-Net model for image segmentation
- Use the Mask R-CNN to perform instance segmentation

![](/assets/images/report/seg-1.png)
![](/assets/images/report/seg-2.png)
![](/assets/images/report/seg-3.png)
![](/assets/images/report/seg-4.png)
![](/assets/images/report/seg-5.png)
![](/assets/images/report/seg-6.png)
![](/assets/images/report/seg-7.png)
![](/assets/images/report/seg-8.png)

semantic segmentation은 픽셀에 레이블을 지정하여 객체를 찾는 방법이다. 각기 유사한 객체는 동일한 클래스에 할당된다.

instant segmentation
