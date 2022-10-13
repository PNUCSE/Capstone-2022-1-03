# 1. 프로젝트 소개
## 프로젝트 명
**제조영상 불량 검출 및 분류 인공지능 학습모델 개발** 프로젝트를 담당하였다.
## 프로젝트 개요
철강 표면의 결함은 불량 철강을 야기하여 붕괴 사고의 원인이 된다.  
하지만 한국의 철강 생산량은 세계 5위권에 달할 정도로 많으므로, 육안으로 이를 모두 판독하기는 어렵다.  
따라서 인공지능 모델을 활용하여 철강 표면의 결함을 검출한다.
## 프로젝트 목적
우리는 이 프로젝트를 통하여 철강 표면의 결함을 검출 및 분류하여 철강 제조 과정에서의 불량률을 낮추고자 한다.
<br/>
# 2. 팀소개
|이름|이메일|역할|
|:---:|:---:|:---:|
|서지훈|tjwlgns02@gmail.com|철강 결함 검출 모델 초기 형태 개발<br/>모델 학습 파라미터 값 조정 및 검증<br/>완성된 모델 최종 검증 및 최적화|
|김무영|andud084417@naver.com|훈련용 데이터 분석 및 전처리<br/>훈련용 데이터 증강<br/>모델 평가 및 결과 분석|
<br/>

# 3. 구성도
![시스템 구성도](https://user-images.githubusercontent.com/62493933/195324072-68b80156-51f9-4c78-a918-902529c80647.png)
<br/>

# 4. 소개 영상
프로젝트 소개 영상 첨부
<br/>

# 5. 사용법
1.[학습에 사용된 데이터 세트](https://www.kaggle.com/competitions/severstal-steel-defect-detection/data?select=train_images)를 input 폴더에 넣어 배치한다.

2.Ubuntu 20.04 버전에서 개발되었으며, Python 3.6.9를 사용한다.

3.프로젝트의 사용을 위해서 아래의 명령어를 통하여 프로젝트에 사용된 라이브러리를 설치해야 한다.  
<br/>
- U-Net 모델을 사용하기 위한 라이브러리
```
pip install segmentation_models
```
- 딥러닝 사용을 지원하는 라이브러리
```
pip install tensorflow==2.4.0
```
- 데이터 세트를 분리하는 기능을 지원하는 라이브러리
```
pip install scikit-learn
```
- 데이터 분석의 시각화를 위한 라이브러리
```
pip install matplotlib
```
- csv 파일을 다루기 위한 라이브러리
```
pip install pandas
```
- 이미지 파일 로드를 위한 라이브러리
```
pip install pillow
```
- 이미지 데이터 증강을 위한 라이브러리
```
pip install imgaug
```
- 이미지 데이터를 행렬로 다루기 위한 라이브러리
```
pip install numpy
```