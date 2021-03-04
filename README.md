# 2021KUBIG_competiton
0. 개요


1. 데이터 전처리
- histogram: 대표값으로 대체
- 평균, 분산
- NA 값에 대한 처리: columnwise 적용. pos null 30%이상 -> pos median, 나머지 -> 전체의 median
- class imbalance: oversampling (SMOTE)
- feature selection: drop over 40% na, 2장 내용 참고, logistic 회귀
- feature reduction: PCA
- columnwise normalizing


2. Trainig Models

3. Performance

4. Key Takeaways
