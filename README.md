# job_train

1. **기간 : 2021.12.06 ~ 01.28** 

0. **팀원**
    1. 씩씩한오리너구리 (https://github.com/DongHyunByun/)

2. **기술스택**
    1. 개발환경 : python.   
    2. 전처리 : pandas, numpy. 
    3. boosting : lgbmClassifier, xgbclassifier, CatBoostClassifier.  
    
3. **내용 : job care 분류**
    1. 여러 컬럼들을 이용하여 class가 0 or 1인 binary classification
    2. 여러 전처리 방법 중 최종적으로 3번 방법 사용
    3. lgbmClassifier, xgbclassifier, CatBoostClassifier 머신러닝 기법 사용
    4. best model : catboost(최종스코어 f1:0.70499)

4. **파일설명**
    1. job_train.ipynb
        - 데이터 전처리  
        - 모델링 및 학습  
        - 예측 및 제출 파일 생성

5. **결과**  
    42위/728명
    
