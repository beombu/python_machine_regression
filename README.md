<h1 align="center">코로나 백신접종자 수에 따른 확진자 수 추이 예측 프로그램</h1>
<p align="center" display="inline-block">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-squaree&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-squaree&logo=Pandas&logoColor=white"> 
</p>

## 프로젝트 소개
회귀 알고리즘을 사용하여 코로나 백신접종자 수에 따라 확진자 수가 어떻게 변화하는지 알아보는 프로젝트입니다.

### 주요기능

#### 1. 오늘의 확진자 수
날짜를 입력받아 해당 날짜의 확진자 수를 구해준다.(ex 2022-06-20)

#### 2. 지역별 확진자 수
서울내 구이름을 입력하여 해당 구의 총확진자 수를 구해준다.(ex 노원구)

#### 3-1. 확진자 수 그래프
x좌표가 날짜, y좌표가 확진자 수인 그래프를 그려준다.

#### 3-2. 누적 예방접종자 수 그래프
x좌표가 날짜, y좌표가 예방접종자 수 인 그래프를 그려준다.

#### 3-3. 회귀 알고리즘 전처리 그래프
x좌표가 누적 예방접종자 수, y좌표가 확진 자 수인 그래프를 그려준다.

## Setup
[서울특별시_코로나19 백신 예방접종 현황](https://www.data.go.kr/data/15078073/fileData.do)</br>
해당 사이트에서 xls을 다운로드 받으시고 Today_vaccination.xls파일로 변경해야 최신 정보 활용 가능합니다.

> //Install OpenAPI</br>
> pip install "api name"</br></br>
> //Run the main1</br>
> python main1.py</br>
