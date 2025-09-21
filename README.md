kaggle의 ecommerce-consumer-behavior-analysis-data 데이터셋 사용  
https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data


1. 데이터의 성별, 나이, 관심있는 상품 카테고리란 사용
2. BERT NLP 알고리즘을 사용하여 광범위하게 나눠져있는 카테고리 데이터를 5개의 클러스터로 군집화
3. CSV의 숫자 및 문제 데이터를 정규화  
   3.1. 나이(숫자) 데이터는 StandardScaler로 정규화  
   3.2. 문자열 데이터인 성별, 상품 카테고리는 원핫 인코딩 정규화  
6. GMM 알고리즘을 이용하여 전체 데이터를 3개의 클러스터로 군집화
7. 새로운 유저 데이터를 학습된 GMM 알고리즘에 적용하여 군집 인덱스를 리턴 받도록 하여 추천 시스템에 활용 가능
