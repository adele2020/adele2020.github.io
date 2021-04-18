# conv1d와 conv2d
CNN은 1D, 2D 또는 3D와 관계없이 동일한 특성을 공유하고 동일한 접은 방식을 따른다. 주요 차이점은 입력 데이터의 차원과 특성 detector(or filter) 가 데이터를 교차하며 silde 할 때의 방식이다.
[E5]_AUDIO_CLASSIFICATION 정리하기

##
Abstract
1. Introduction

2. Related Work
- Residual Representations
- Shortcut Connections

3. Deep Residual Learning
3.1. Residual Learning
3.2. Indentity Mapping by Shortcuts
3.3. Network Architectures
- Plain Network.
plain baseslines은 주로 VGGNet 의 철학에서 영감을 받았다.
convolution layers 은 주로 3x3 필터들이고 두가지 간단한 디자인 규칙을 따른다.
1) 동일한 feature map 크기에 대해 layers 는 동일한 수의 filter를 가진다.
2) feature map 크기가 절반으로 줄어들면 필터 수가 두배로 늘어나 계층당 시간복잡도를 보존한다.
stride 2인 convolution layers에 의해 직접 downsapling을 수행한다.
network는 global average plooling layer와 softemax를 가진 1000-way fully-connected layer로 끝난다.
plan model은 vgg nets 보다 복잡도가 낮고, 필터수가 적다는 것을 알아둘 필요가 있다.
우리의 34-layer baseline 은 36억 FLOPs(multiply-adds)이고, vgg-19보다 18%에 불과하다.
- Residual Network.
Plan Network를 기반으로 해서 sortcut connections를 삽입하여 이 네트워크의 상대가 되는 residual version으로 전환한다.
input과 output이 동일한 차원일 때 identity shortcuts을 직접 사용할 수 있다.
차원이 증가하면 두가지 옵션을 고려한다.
1) 차원 증가를 위해 zero entry가 추가로 padding된 상태로 identity mapping을 수행한다. 이 옵션은 parameter를 추가하지 않는다.
2) projection shortcut은 차원을 일치 시키는데에 사용된다. (1x1 convolutions에 의해)
두 옵션은 모두 sortcuts이 두 사이즈의 feature map을 가로 지르면서 stride 2로 수행된다.

3.4. Implementation
- ImageNet에 대한 구현은 관행에 따른다.
- 스케일 확대를 위해 [256, 480]에서 랜덤하게 샘플링된 짧은 면으로 이미지의 크기를 조정한다.
- 랜덤하게 샘플된 이미지를 224x224 crop 하거나 수평 flip, with 픽셀당 평균 subtracted
-

4. Experiments
4.1. ImageNet Classification
- Plain Networks.
- Residual Networks.
- Identity vs. Projection Shortcuts.
- Deeper Bottleneck Architectures.
  + 50-layer ResNet
  + 101-layer and 152-layer ResNets
  + Comparisons with State-of-the-art Methods.
4.2. CIFAR-10 and Analysis
- Analysis of Layer Responses.
- Exploring Over 1000 layers.
4.3. Object Detection on PASCAL and MS COCO  
