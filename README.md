# Wallmart 데이터 분석

## 프로젝트 개요
[Kaggle의 Wallmart 데이터 셋](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset) 분석 프로젝트입니다. 데이터 전처리, 탐색적 데이터 분석(EDA)을 통한 데이터의 분포를 확인하고, VIP 고객 도출 및 지역별 구매 고객 특징을 파악하여 마케팅 전략을 도출합니다.
이 프로젝트의 목표는 주어진 데이터의 분포를 분석하여 주요 특징을 도출하고, 이를 바탕으로 마케팅 전략을 제시하는 것입니다.

## 데이터 설명
- 데이터 출처: [Kaggle의 Wallmart 데이터 셋](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset) 
- 데이터 상세: 약 55만개의 사용자 거래 내역과 10개의 특징(550068, 10)
  - `User_ID`: User ID
  - `Product_ID`: Product ID
  - `Gender`: Sex of User
  - `Age`: Age in bins
  - `Occupation`: Occupation(Masked)
  - `City_Category`: Category of the City (A,B,C)
  - `StayInCurrentCityYears`: Number of years stay in current city
  - `Marital_Status`: Marital Status
  - `ProductCategory`: Product Category (Masked)
  - `Purchase`: Purchase Amount

## 분석 과정
1. 탐색적 데이터 분석(EDA)
   - 주요 통계 지표 확인
   - 각 변수의 분포 시각화
2. 마케팅 전략 도출
- 프로젝트 목표: 데이터 분석을 통한 마케팅 전략 제안
  1) VIP 고객을 찾아서 고객 맞춤 프로모션 제안
    - 고객의 구매금액 기준, 구매금액 합계가 가장 높은 Top10
    - 고객의 구매금액 기준, 구매금액 평균이 가장 높은 Top10
    - 고객의 구매 항목 개수 기준, 가장 많은 항목을 구매한 고객 Top10
    - 위의 고객들의 성별, 연령, 직업, 지역, 결혼 여부, 제품 품목에 대한 분석
    - 분석 결과를 바탕으로 고객 맞춤 프로모션 관련 제언

  2) 지역별 소비 패턴 분석을 통한 제품 카테고리 제안
    - 각 지역별 판매 금액 합계, 사용자 수, 사용자의 연령, 직업, 결혼 여부 분석
    - 각 지역별 특징 도출
    - 각 지역별 소비 패턴 기반 매장 운영 방법 제언
 
## 주요 결과 및 성과
- VIP 고객의 주요 특징 발굴 및 그에 따른 마케팅 전략 제언
- 지역별 소비 패턴 분석을 통한 매출 강화 전략 제언

## 필요한 라이브러리
- pandas
- seaborn
- plotly
