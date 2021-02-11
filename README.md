# AI Campus Final Project

## 프로젝트 개요

### 프로젝트 명

- 이미지 기반 여행지 추천 서비스 - 좋은 날

### 프로젝트 기간

- 2020.10~ 2020.11

### 프로젝트 목적

- 이미지 분류 알고리즘을 통해 사용자가 입력한 데이터와 가장 유사한 데이터를 추천
- 사용자가 쉽게 접근할 수 있는 UX/UI를 제공하는 모바일 화면에 최적화 된 웹사이트 제작


## 개발 환경

### WEB
- Django, Nginx, gunicorn
- AWS EC2 Server

### MODELING
- TensorFlow Keras


## 세부 사항

### 구현 기능

- 여행지 추천 기능 : 지역, 키워드를 선택하여 해당하는 여행지 목록 나열
- 여행지 검색 기능 : 이미지를 첨부 -> 첨부한 이미지와 가장 유사한 장소 추천
  - AI Hub에서 제공되는 랜드마크 이미지 + 스크래핑한 여행지 이미지 데이터를 정제하여 학습
  - Resnet알고리즘 선택하여 학습 후 성능 검증

- 추천 받은 여행지 위치 및 주변 정보 제공

### 주요 특징

- database를 따로 사용하지 않은 lite한 웹
- 다양한 API와 데이터 활용
- 모바일 환경 맞춤 제작


## 상세 화면
<img src="https://user-images.githubusercontent.com/64633169/107618120-63c8dd80-6c94-11eb-9ba3-19210c17f79f.png" width="500">
<img src="https://user-images.githubusercontent.com/64633169/107618236-94107c00-6c94-11eb-8245-55842a337e87.png" width="500">
<img src="https://user-images.githubusercontent.com/64633169/107618250-98d53000-6c94-11eb-867d-78e2af3cedc5.png" width="500">


