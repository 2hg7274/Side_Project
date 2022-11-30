# 월간 데이콘 신용카드 사기 거래 탐지 AI 경진대회 
비지도 학습과 이상치 탐지 공부를 해보기 위채 진행한 프로젝트입니다.  

## 📝 프로젝트 리포트
[프로젝트에 대한 자세한 설명 (코드 설명 포함)](https://cooing-howler-35f.notion.site/AI-790b3a199c8445e38a4768004c5f0125)  

## 📂 파일 설명 
#### Scikit-learn과 Tensorflow의 Anomaly Detection 방법
1. **EllipticEnvelope**  
  - [elipticenvelope.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/elipticenvelope.ipynb) / scikit-learn의 elliptic envelope 방법.  
  - [elipticenvelope_2.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/elipticenvelope_2.ipynb) / `model.score_samples()`을 통해 음수 Mahalanobis 거리를 계산하는 방법. (public 점수: 0.9305289388
/ private 점수: 0.9080859389)  

</br>  
</br>  

2. **IsolationForest**  
  - [isolationforest.ipynb](https://github.com/2hg7274/Competition/blob/main/Dacon/Credit_fraud_detectoin/isolationforest.ipynb) / scikit-learn의 isolation forest 방법.  

</br>   
</br>  

3. **AutoEncoder**  
  - [autoencoder.ipynb](https://github.com/2hg7274/Side_Project/blob/main/Dacon/Credit_fraud_detectoin/autoencoder.ipynb) / 1D AutoEncoder 방법.  
  (public 점수: 0.906307551 / private 점수: 0.8868897234)  



</br>   
</br>  

4. **MissForest_KNN**  
  - [missforest_oversampling_knn.ipynb](https://github.com/2hg7274/Side_Project/blob/main/Dacon/Credit_fraud_detectoin/missforest_oversampling_knn.ipynb) / 결측값 대체(missing imputation) 방법을 사용한 train dataset 라벨링, KNN 모델로 이상치 탐지.  
  (public 점수: 0.9306109751 / private 점수: 0.9051944159)

</br>  
</br>  

- [eda.ipynb](https://github.com/2hg7274/Side_Project/blob/main/Dacon/Credit_fraud_detectoin/eda.ipynb) / validatoin dataset correlation analysis 

## 데이터 출처 
[https://dacon.io/competitions/official/235930/data](https://dacon.io/competitions/official/235930/data)
