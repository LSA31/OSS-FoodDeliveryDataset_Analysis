# Food Delivery Dataset Analysis
이 프로젝트는 Kaggle에서 제공하는 'Food Delivery Dataset'을 분석하여 배달 시간을 예측하는 것입니다. 이 데이터 세트에는 주문 날짜, 주문 시간, 배달원 정보, 식당 위치, 배달 위치, 날씨 상황 등의 정보가 포함되어 있습니다.

## 데이터셋
이 데이터 세트는 Kaggle에서 API로 다운로드 받을 수 있습니다. 아래의 코드를 사용하여 데이터셋을 다운로드 받을 수 있습니다.

https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset/data

## 데이터 전처리
데이터 전처리 과정에서는 다음과 같은 작업을 수행합니다.

필요없는 열 제거

결측치 처리

날짜 및 시간 관련 특성 생성

주문 준비 시간 계산

식당 위치와 배달 위치 간의 거리 계산

레이블 인코딩

모델 학습

여러 모델을 학습시킨 후, 가장 높은 R2 점수를 가진 모델을 선택합니다. 이 프로젝트에서는 XGBoost 모델이 가장 높은 R2 점수를 보였습니다.

## 모델 평가
모델의 성능은 Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), 그리고 R-squared (R2) Score를 사용하여 평가합니다.

## 추가 분석
각 도시별로 배달 시간의 통계를 계산하여 추가적인 분석을 수행하였습니다.

코드의 자세한 내용은 아래를 참조해주세요.

## GitHub Repository


사용된 도구: 

Python

Pandas

Numpy

Scikit-learn

Matplotlib

Seaborn

XGBoost
