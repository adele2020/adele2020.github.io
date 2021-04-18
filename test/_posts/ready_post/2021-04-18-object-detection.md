---
title:  "Distinguish between object localization and object detection"
excerpt: ""
categories:
  - 또다른정리
tags:
  - Object Detection
use_math: true
year-archive: 2021
last_modified_at: 2021-04-18T17:15:00-00:00
---
Multi-Class classification 과 Muti-Label classification을 구분해서 생각해야 한다.
Muti-Label classification은 예를 들어 주어진 이미지에 있는 모든 다른 항목과 사람을 식별 할 수 있다.

object detection과 object localization을 구별해야 한다.
object localization은 이미지의 주요 주제 주위에 경계 상자를 표시하는 반면 object detection은 이미지 내의 모든 객체 주위에 경계 상자를 표시한다.

bounding box를 예측하기 위해 output dense layer에서 regression이 사용된다.

IoU는 두 bounding box의 합집합 영역으로 두 bounding box의 교집합 영역을 나눈 것이다.

IoU값이 0에 가까우면 bounding box의 예측이 좋지 못한 값이고,
IoU값이 1에 가까우면 bounding box의 예측이 좋은 편이다.
