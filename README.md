# YJU Interm Report

## 조원

<table>
  <tr> 
    <td align="center"><a href=https://github.com/Hannah0su><img src="https://user-images.githubusercontent.com/102000749/165738552-60e1eac0-3c50-4568-ae38-767c44b3b018.jpg" width="100px;" alt=""/><br /><sub><b>Ha Youngsu</b></sub></a><br /><a href="https://hannah0su.github.io/" title="Code">🏠</a>
    </td>
    <td align="center"><a href=https://github.com/ooyniz><img src="https://user-images.githubusercontent.com/83005178/166416247-3908c2e9-ed1c-4e44-aa6a-68f3db0f45db.png" width="100px;" alt=""/><br /><sub><b>Kwak Yujin</b></sub></a><br />🏠
    </td>
    <td align="center"><a href=https://github.com/baegjhoon><img src="https://user-images.githubusercontent.com/102000749/165739357-9ea66cf1-8a6e-4b9a-bf77-0a8c9e1a465a.png" width="100px;" alt=""/><br /><sub><b>Baeg Junghun</b></sub></a><br />🏠
    </td>
    <td align="center"><a href=https://github.com/sila0319><img src="https://user-images.githubusercontent.com/102000749/165739259-24741b3b-92d2-49df-8496-7dab8f58bd97.png" width="100px;" alt=""/><br /><sub><b>Ryu wonkyu</b></sub></a><br />🏠
    </td>
  </tr>
</table>

<br>
<br>

---

## 1번과제 

---
<br>

## 2번과제 

<br>

## 딥러닝(Deep Learning) 이란?

인간의 뇌가 가지는 생물학적 특성 중 뉴런의 연결 구조인 신경망을 모방해 인공신경망(Artificial Neural Network, ANN)을 만들어냈으며, 딥러닝은 여러 층을 가진 인공신경망을 사용해 머신러닝 학습을 수행한다.

딥러닝과 머신러닝의 차이는 머신러닝은 특징 추출(Feature Extraction)을 개발자가 해야 하지만, 딥러닝은 자동으로 특징 추출을 한다는 것이다. 

**대규모 데이터에서 자동으로 특징을 추출해 중요한 패턴 및 규칙을 학습하고, 이를 토대로 의사 결정이나 예측 등을 수행하는 기술**


---

## 퍼셉트론 이론

![perceptron](https://user-images.githubusercontent.com/83005178/166610052-fef66184-5cae-49ec-9fce-086e46a4f0b0.png)

1957년, 퍼셉트론 이론이 발표되었으나, 기술적 한계에 부딪혔다.  
이러한 한계는 2000년대에 도달해서야 극복할 수 있는 방법이 제안되었다.  
이후 딥러닝은 미래를 선도할 혁신 기술의 하나로 각광받고 있다.  

---

## 딥러닝의 도약 배경

<br>

1. 기존의 인공신경망 한계를 극복할 수 있는 알고리즘의 개발
다층 퍼셉트론과 역전파 알고리즘을 통해 기존의 한계를 극복했다. 이외에도 과적합(Overfitting)을 방지하기 위한 Dropout 알고리즘이 개발됨.

2. 인터넷을 통해 축적된 엄청난 양의 빅데이터
3. GPU기반의 병렬처리를 포함한 컴퓨팅 파워의 발달  

---

## 2번과제에서 어떤 것들을 탐구하나요?

### 이미지 분류

![귀여운 강아지와 고양이](https://user-images.githubusercontent.com/83005178/166610083-91454044-91dc-4ab2-bfb9-ffa4b517d7e2.jpg)

### CNN계열 -> VIT 까지의 흐름

lenet -cnn 으로 숫자분류

![lenet](https://user-images.githubusercontent.com/83005178/166613918-ff64d687-0d3f-4aaa-9908-ff478f1ef3c4.jpg)

alexnet 이미지넷에 cnn 시도

![alexnet](https://user-images.githubusercontent.com/83005178/166613947-98361f5b-f1d1-40e6-92d0-5706cd9a0d65.png)

vggnet - 커널 사이즈를 작게, 깊은 모델일수록 성능 향상

![vggnet](https://user-images.githubusercontent.com/83005178/166614031-5e8038cc-3ba1-43cb-86a4-ed329ac8544e.png)


resnet - 더 깊은 모델을 만드는 방법 제안, 기존의 DNN 모델들이 단순히 layer을 많이 쌓으면 더 성능이 좋아지는 줄 알았지만

그 레이어가 깊어지는 과정에서 vanishing gradient problem등 오히려 학습이 더 안되는 문제가 있었고 이를 해결하는게 shortcut을 도입한 resnet이다

![resnet](https://user-images.githubusercontent.com/83005178/166614084-cd2e9f24-d260-415d-b96d-ef867d9b5510.jpg)

ViT - 자연어에서 사용한 transformer를 이미지 분류에 도입. 거대데이터셋으로 학습시켜 좋은 성능

![vit](https://user-images.githubusercontent.com/83005178/166614403-ae716878-6744-4f5f-9dd5-c35fc1400174.png)


### 발전의 배경과 기반 지식

convolution  
layer  
shortcut  
gradient  
**VGP(vanishing gradient problem)**  

---

