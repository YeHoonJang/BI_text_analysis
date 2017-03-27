

# 가천대학교 산업경영공학과 고객관리 Team Project


**본 Repositroy는 review를 통한 평점 예측하기 프로젝트 입니다.  **


## 프로젝트 설명

이 프로젝트는 Amazon의 책 review를 분석하여 작성자의 평점을 예측하는 모델을 구축합니다.


## Team

   - 서예지(yejiyeji94@gmail.com)
   - 장예훈(jangyh0420@gmail.com)
   - 조용걸(yonggeol93@gmail.com)


## Data Set

   - Amazon product data (http://jmcauley.ucsd.edu/data/amazon/), Books

## To Do List

   1. Data 전처리
   
        - 데이터에서 Review와 Overall text를 추출. (Asin보류)
        - 숫자, 관사, 고유명사, 특수문자 제거
        - 문장단위로 끊고, 문장내에서 형용사가 있는 문장 추출.
        - 추출화 된 문장에서 부사제거
   
   2. Neural net
   
        - 전처리 한 데이터를 Input data에 넣고 overall을 output data로 설정하여 neural net방법으로 학습


## 참고자료

   - Building Machine Learning Systems with Python, 2013, Packt Publishing
