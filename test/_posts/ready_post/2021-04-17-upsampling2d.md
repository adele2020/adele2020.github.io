UpSampling2D 와 Conv2DTranspose의 차이

UpSampling2D는 케라스 기준 내부적으로 resize_images() 를 호출한다. 즉, 적은 해상도를 일부러 고해상도로 올리는것이다. 단순히 잡아 늘리는 역할으로 바로 Conv2D의 함수가 호출되어야 될 필요가 있음
Conv2DTranspose는 Convolution 연산이 들어가서 해상도를 키운다. 이 연산은 당연히 학습과정에서 필터가 학습이 된다.
보통은 H, W가 줄어들고 Feature map갯수에 따라 차원이 늘기 때문에 익숙한 개념은 아니지만, 패딩을 적당히 섞으면 H, W가 늘어나는것도 당연히 가능하다.
