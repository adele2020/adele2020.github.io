---
title:  "[6주차] Aiffel에서 인공지능 도전기"
excerpt: "컴퓨터 파워 UP 해커톤 Convolutional Networks"
categories:
  - SSACxAIFFEL
tags:
  - 주간정리

year-archive: 2021
last_modified_at: 2021-02-05T00:00:00-00:00
---

## FUNDAMENTALS  
#### 16. 컴퓨터 파워 UP  
멀티태스킹, 병렬프로그래밍과 동시성에 대해 이해한다. 파이썬으로 멀티스레드와 멀티프로세스를 구현하는 법에 대해 학습한다.  
>`사실 해커톤을 준비한다고 주의 깊게 보진 못했다. 시간이 된다면 다시 살펴봐야 할 거 같다.`

## 해커톤  
#### Predict Future Sales  
Description :  
This challenge serves as final project for the "How to win a data science competition" Coursera course.  

In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company.  

We are asking you to predict total sales for every product and store in the next month. By solving this competition you will be able to apply and enhance your data science skills.  

Evaluation :  
Submissions are evaluated by root mean squared error (RMSE). True target values are clipped into [0,20] range.  

Submission File  

For each id in the test set, you must predict a total number of sales. The file should contain a header and have the following format:  

ID,item_cnt_month  
0,0.5  
1,0.5  
2,0.5  
3,0.5  
etc.  
>`출제를 분류 문제로 낼 줄 알았는데, 시계열의 회귀가 나왔다. 시계열은 아직 노드에서 배우지 않았다. 하지만 이 데이터로 가능성을 보려한거 같기도 하다. 처음하는 캐글이고, 프로젝트 조원들이랑 대면하게 되어서 긴장이 되기도 했다. 프로젝트는 개인적으로 조금 아쉬움이 남는다. 다양한 모델을 사용해 보고, 하이퍼파라미터 튜닝도 시도해봤어야 하는데, 짧은 시간에 다 해내긴 힘들었다. 이번 프로젝트로 상생이 중요하다는 것을 깨달았다.`

## DeepML    
CS231n Lecture 7: Convolutional Networks
>`노드에서 Deep Leaning 을 진행할 때 layer 에 대한 이해가 필요했는데 이번 시간이 답을 주고 있었다. 완벽히 이해한 것은 아니지만 프로그램에서 layer를 만들 때 코드에 들어가는 많은 숫자들이 그냥 있는 것이 아니구나라는 걸 알았다.`

## 일주일 간의 느낀 점  
상생이 중요하다는 것을 느꼈다. 다음 해커톤은 좀 더 멋지게 해내고 싶다.   
