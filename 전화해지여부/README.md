## 전화해지여부 예측 경진대회
- 프로젝트 참여 기간 : 2023/02/21 ~ 2023/02/27

- 프로젝트 문제 : 고객 전화 사용 데이터를 바탕으로 한 전화해지여부 분류예측

- 사용 데이터 : train/test/submission 데이터 참고

- 대회 링크 : [DACON Basic 전화해지여부예측](https://dacon.io/competitions/official/236075/overview/description)
<br/>

## Codes
1. [제출코드1](cal_cancel_real.ipynb) : Data Preprocessing + Feature Engineering + AutoML 과정을 거쳐 제출한 방법(최고 성능)
2. [제출코드2](cal_cancel_real_2.ipynb) : Data Preprocessing + Feature Engineering + Stacking(ExtraTree & LightGBM & CatBoost & XGBoost) 방식을 활용하여 제출한 방법