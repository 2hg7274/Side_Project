# 월간 데이콘 신용카드 사기 거래 탐지 AI 경진대회 
비지도 학습과 이상치 탐지 공부를 해보기 위채 진행한 프로젝트입니다.  

## 📝 프로젝트 리포트
[프로젝트에 대한 자세한 설명 (코드 설명 포함)](https://cooing-howler-35f.notion.site/AI-790b3a199c8445e38a4768004c5f0125)  

## 📂 파일 설명 
#### Scikit-learn의 Anomaly Detection 방법
1. **EllipticEnvelope**  
  - [elipticenvelope.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/elipticenvelope.ipynb) / scikit-learn의 elliptic envelope 방법.  
  - [elipticenvelope_2.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/elipticenvelope_2.ipynb) / `model.score_samples()`을 통해 음수 Mahalanobis 거리를 계산하는 방법. (public 점수: 0.9305289388
/ private 점수: 0.9080859389)  

2. **IsolationForest**  
  - [isolationforest.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/isolationforest.ipynb) / scikit-learn의 isolation forest 방법.

## 데이터 출처 
[https://dacon.io/competitions/official/235930/data](https://dacon.io/competitions/official/235930/data)
