# AlexNet-bird-classifier-lowres
AlexNet모델을 활용한 저해상도인 조류 이미지 분류 프로젝트입니다.
<br><br>

## 🖥️ 개발환경
* <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white">
<br>

## ➡️ 프로젝트 흐름
1. 데이터 수집: 데이콘(저해상도 조류 이미지 분류 AI 경진대회)
2. 이미지 전처리: 저해상도(64×64)이미지를 (224×224)사이즈로 만들기 위해 '랭쵸스 보간법(Lanczos resampling)'을 활용하여 전처리 진행
3. label값이 있는 train 데이터를 train:val:test(70:15:15)로 나누어 활용
4. AlexNet 모델 활용
5. 예측 결과 시각화
<br>
![img](https://github.com/Yu-Hyemin/AlexNet-bird-classifier-lowres/blob/c85269ac654ff26e71d398fea2628f9bd4c70d64/results_img.png)
