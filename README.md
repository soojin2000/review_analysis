# 토픽모델링과 감성분석을 이용한 화장품 리뷰 분석
본 프로젝트에서는 화장품의 리뷰 텍스트를 이용해 더 가시적이고 직관적인 형태의 리뷰 시스템을 개발하고자 했다. 
### 1. 전처리(Preprocessing)  
-데이터 크롤링 : 올리브영의 '크림' 제품군 리뷰 크롤링  
-전처리 : 데이터 정제, 형태소 분석 및 토큰화, 합성명사 처리  
-피부타입 재분류 : NoneType 데이터 중 일부를 리뷰 내용을 통해 건성, 지성, 복합성으로 재분류
  
  
### 2. 토픽모델링(LDA & Word2Vec & Spliting sentences)
- LDA : 리뷰에서 평가 요소(토픽) 도출  
- Word2Vec : LDA로 도출한 토픽의 키워드 추출  
- Spliting sentences : 

### 3. 감성분석(Sentiment Analysis)

### 4. 시각화(Visualization)
