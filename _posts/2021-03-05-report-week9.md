---
title:  "[9주차] Aiffel에서 인공지능 도전기"
excerpt: ""
categories:
  - SSACxAIFFEL
tags:
  - 주간정리

year-archive: 2021
last_modified_at: 2021-03-05T17:15:00-00:00
---

## FUNDAMENTALS
#### 23. 맵리듀스로 그리는 빅데이터 지도
맵리듀스의 기본 로직을 이해하고 파이썬으로 간단히 체험해 본다.
#### 24. 딥러닝 레이어의 이해(1) Linear, Convolution
딥러닝에서 레이어의 개념을 이해하고, 그 중 Linear 레이어와 Convolution 레이어에 대해 보다 자세하게 알아본다.
>`맵리듀스 개념을 배웠다. 하둡을 배울 때 맵리듀스를 알게 되었는데, python 코드로 맵리듀스 개념을 설명하는 것이 신기했다. 맵리듀스를 많은 것을 잘게 나누어서 각각을 처리한 후에 처리된 것들을 모아서 통합 결과물을 낸다라고 정리를 했다. 맵리듀스가 나왔으면 하둡과 하둡ecosystem들이 나와야할텐데... 그건 차후에 다루려나보다. 24.딥러닝 레이어의 이해(1)에서는 그동안 배웠던 Linear, Convolution을 다시 한번 이해시킨다. 사실 DeepML 시간과 스터디에서 배웠었지 노드에서는 자세히 나오지 않았는데, 이번 노드에서 개념 정리를 한 거 같다. Fully Connected Layer, Feedforward Neural Network, Multilayer Perceptrons, Dense Layer… 등 다양한 이름으로 불리지만 모두 Linear layer이다. Linear 레이어는 선형 변환을 활용해 데이터를 특정 차원으로 변환하는 기능을 한다. Convolution layer, Pooling Layer, Deconvolution 에 대해서 배웠다.`

## EXPLORATION  
#### 15. 트랜스포머로 만드는 대화형 챗봇 [>>프로젝트 보기](https://github.com/adele2020/ssacxaiffel/blob/main/%5BE15%5D_korean_chatbot.ipynb)
트랜스포머의 인코더 디코더 구조와 셀프 어텐션을 코드를 통해 이해해 본다. 이를 영어와 한국어로 이루어진 챗봇 데이터에 적용해 본다.
#### 16. 흐린 사진을 선명하게 [>>프로젝트 보기](https://github.com/adele2020/ssacxaiffel/blob/main/%5BE16%5D_SRGAN.ipynb)
저해상도 이미지를 고해상도로 변환해 주는 Super Resolution 의 대표적인 2개 구조(SRCNN, SRGAN)에 대해 이해하고 활용해본다.
>`흥미로운 주제의 NLP과 CV 프로젝트였다. 15.노드에서 배운 트랜스포머는 기존의 RNN과 CNN을 쓰지 않기 때문에 recurrent, convolution 연산을 하지 않는다. 그래서 전체적인 계산의 복잡도가 dot product라는 심플한 연산만을 사용하기 때문에 감소했고, 병렬 처리가 가능해졌으며, long range path가 가지고 있던 문제를 해결했다. attention의 과정을 시각화 하기 쉬워져 더욱 더 해석 가능한 모델이다. 16.노드에서 배운 Super Resolution은 기법들은 재미있었다. 물론 모델이 일부 class와 많지 않은 데이터로 학습되었기 때문에 성능은 좋지 않았지만 Super Resolution의 과정은 신기할 따름이였다. `  

## DeepML   
CS231n Lecture 11: Training Neural Networks II
>`학습을 어떻게 하면 잘 할 수 있는지에 대한 방법을 소개한 내용이다. learning rate schedule은 어떻게 가져갈 것인지 Hyperparameters를 선택하는 방법과 과정을 소개했다. 유용한 자료이다. 쉽진 않겠지만, 차후에 모델 훈련을 할 때 참고하면 좋을 거 같다.`

## 코딩마스터   
Do it! 자료구조와 알고리즘 입문: 3. 검색 알고리즘
>`검색알고리즘중 선형 검색, 이진 검색, 해시법에 대해 배웠다. 선형검색은 직선 모양(선형)으로 늘어선 배열에서 검색하는 경우에 원하는 키값을 가진 원소를 찾을 때까지 맨 앞부터 스캔하여 순서대로 검색하는 알고리즘이다. 검색 비용을 줄이기 위해 검색할 값을 배열의 맨 끝에 추가하는 보초법이 있다. 이진 검색은 일정한 규칙으로 늘어놓은 데이터 집합에서 아주 빠른 검색을 수행할 수 있고, 해시법은 삭제가 자주 일어나는 데이터 집합에서 아주 빠른 검색을 수행한다. 해시법에는 같은 해시값 데이터를 연결 리스트로 연결하는 체인법과 데이터를 위한 해시값이 충돌할 때 재해시하는 오픈 주소법이 있다.`  

## 일주일 간의 느낀 점
통제할 수 있는 것과 통제 할 수 없는 것을 구분해야 하는데 구분하지 못하고 있다.
