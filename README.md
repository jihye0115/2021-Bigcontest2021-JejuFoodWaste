# 빅콘테스트 2021, ECO 제주 분야 최우수상
### ['그린핀치'팀 최종 발표 영상 클릭](presentation-link)

## 문제 정의
2021년 7, 8월 두 달 간의 41개 행정동별 제주도 음식물 쓰레기 배출량을 예측하고, 감소 방안 제시하기
<br> 

## 사용 데이터
- 제공 데이터 : 제주도 음식물 쓰레기 배출량, 유동인구, 카드 소비량 데이터
- 외부 데이터 : 상가 정보, 가구 정보, 기상 관측, 학교 개수, 주가, 물가지수, 코로나 확진자 수, 검색어 (코로나, 관광 관련), 공휴일 데이터
<br>

## 학습 및 검증 기간
- 학습 : 2018년 1월 ~ 2021년 4월
- 검증 : 2021년 5월 ~ 6월
- 결과 예측 : 2021년 7월 ~ 8월
<br>

## 분석 과정
1. EDA 
2. feature engineering - 카드 파생 변수, 클러스터링 변수 생성
3. 미래 시점의 설명변수 예측 - 2021년 7, 8월의 유동인구 예측
4. 모델링 - 최종 모형 CatBoost
5. 결과 해석 - shap value
<br>

## Collaborator
고정욱 <br>
[김이현](https://github.com/IhyeonKIM ) (@IhyeonKIM) <br>
[박지원](https://github.com/jiwonlydia) (@jiwonlydia) <br>


[presentation-link]:(https://youtu.be/bx2k0cbR4bE?t=8776)
