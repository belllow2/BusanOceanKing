# BunsanOceanKing Project
해상 교량 데이터에 대한 EDA 및 전위 예측 프로젝트 \

# 분석대상
## 광안대교
* MP25
* 앵커리지
## 남항대교
* P6
* 충돌방지턱

# 데이터셋	
데이터셋은 CSV 파일 확장자로 아래와 같은 형태
|datatime|temperature|salinity|condolence|electricPotential|
|-|-|-|-|-|
|1970-01-01 00:00:00|23|23.7|33.8|-880|

* datetime : 센서 측정 날짜와 시간(ISO8601 포맷)
* temperature : 측정 수온
* salinity : 측정 염도
* condolence : 측정 조위
* electricPotential : 측정 전위차(-mV)
* Data Call time : eletricPotential -> 1H, Temp,Salinity,Condol -> 5M

# Dependencies
* pandas >= 1.0.0
* fbprophet >= 1.0.0
* PyStan >= 2.19.1.1
* numpy >= 1.0.0
* matplotlib >= 3.0.0
* seaborn >= 0.1.0
* xgboost >= 1.3.0
* sklearn
* prophet >= 1.0.0


# Acknowledgements

[Prophet](https://facebook.github.io/prophet/)
