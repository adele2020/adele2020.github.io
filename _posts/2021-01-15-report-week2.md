---
title:  "[2주차] Aiffel에서 인공지능 도전기"
excerpt: "딥러닝은 아직 모르겠다."
categories:
  - SSACxAIFFEL
tags:
  - 주간정리

year-archive: 2021
last_modified_at: 2021-01-15T00:00:00-00:00
---

## FUNDAMENTALS
#### 4. 텍스트의 다양한 변신 (문자열, 파일 다루기)   
텍스트 데이터는 어떻게 처리하는지, 텍스트 파일의 종류는 무엇이 있는 지 살펴보고 연습해 봤다.
#### 5. Data 어떻게 표현하면 좋을까? 배열(array)과 표(table)
Numpy와 Pandas를 통해 파이썬에서 데이터를 행렬과 테이블의 형태로 다루고 표현하는 방법을 익혔다.
#### 6.딥러닝과 신경망의 본질
딥러닝과 신경망에 대해 알아보기.

> ``4. 5. 과정에서 파이썬의 기초 이모저모를 배웠다. 간단한 언어인 거 같은데, 익숙해 지지가 않는다. syntax도 잘 기억이 나질 않고, 아직 몸에 스며들지 않아서 인듯하다. pandas는 유용할 거 같다. R언어처럼 데이터프레임을 손쉽게 처리해줄 수 있는 것이 필요했을 때, pandas를 만났었다. 배울게 자꾸 늘어나고, 완주하지 못 한 책만 쌓여 갈 때 pandas를 위한 책을 또 사야 하나 고민했었다. 욕심을 버려야 한다. FUNDAMENTALS 이 정도로 만족하자. '6.딥러닝과 신경망' 과정에서 뭔가를 발견한거 같다. Nural Net 즉 신경망을 블랙박스라고 말한 사람에게 냉소를 퍼붓는 걸 발견했다. 수학 좀 모른다고 그렇게까지...ㅎㄷㄷㄷ``

## EXPLORATION  
#### 3. 카메라 스티커앱 만들기 첫걸음
얼굴인식 카메라의 흐름을 이해 한 후 dlib 라이브러리를 사용하고, 이미지 배열의 인덱싱 예외 처리를 연습해 봤다.
#### 4. 영화리뷰 텍스트 감성분석하기
imdb 영화 리뷰 평점 데이터를 토대로 사용자들의 리뷰 감성을 분류해 보는 실용적인 텍스트 분류 모델을 구현했다.

> `프로젝트가 점점 더 어려워진다. 라인 수도 많아지고, 파라미터도 많아지고... EXPLORATION 과정은 말 그대로 탐구라고 했다. 어떤 AI분야에 관심을 가지고 집중해볼지 살펴보는 시간이라고 했다.  
재미난 주제의 두 프로젝트였는데, 아직 내 마음이 움직이질 않는다. 카메라 스티커앱은 얼굴사진에서 얼굴의 landmark를 예측하고 적절한 위치에 스티커를 놓는 작업이다. 영화리뷰 텍스트 감성분석은 말 그대로 리뷰 텍스트를 분석하여 감성이 긍정인지 부정인지를 예측하는 모델을 만드는 것이다. 프로젝트를 마쳐야 한다는 조급함에 두 프로젝트를 제대로 탐구해 보지 못한 탓일까? 아직 엄첨나게 재미나고 그렇진 않다. `  

## DeepML   
CS231n Lec03 Image Classification
> `어려운 내용이다. 간단히 이해할 수 있을거 같은데, 영어와 수학 기호가 짬뽕으로 닥쳐오니 너무나 어려워진다. 이해해보려고 경북대 교수님의 한국어로 해석된 강의를 듣고 있다. Lecture03에서 Cross Entropy Loss를 추가 특강으로 강의 하신 것이 있는데, Odds, Logit, Logistic 함수, Logistic Regression, Softmax Fuction, Entropy, Cross Entropy, Cross Entropy Loss Function까지 상세히 진행된다. 신경망을 블랙박스라 말했다고 냉소를 퍼붓는 사람에게 당하고 싶지 않다면 이 강의를 숙지해야겠다는 생각을 했다. 강의를 듣긴 했지만 여전히 블랙박스다.`


## 코딩마스터   
6장 문자열 조작
> ``시간이 없다는 핑계와 어렵다는 핑계로 사전 학습을 하지 못했다. 책만 읽고 참여했다. 정성스레 코드를 작성해온 님들에게 미안하고, 부끄러웠다. 이번 주 주말에는 꼭 시간을 내어 문제를 풀어봐야겠다. 과연 가능할까...``

## Writing
> ``어려운 시간이다.``  

## 일주일 간의 느낀점
조금은 익숙해진 듯 하다. 처음 참여하기 전에는 미지의 세계에 들어가는 느낌이라 허겁지겁 우왕좌왕 했는데, 이젠 아~ 이렇게 진행하는 구나 싶고, 내 시간을 잘 써야겠다고 생각했다.
취할 건 취하고, 버릴 건 버려야 한다.