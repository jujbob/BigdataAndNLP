# BigdataAndNLP
It is a repository for providing slides and codes for this class

# 조별 Github URL

## 0조 임교수
 - 선별종목: 넷마블
 - 전략, 각 조별 분석 자료를 토대로 투자 결정
 - 4월 28일 매수, 투자금액 6000만원 
 - 5월 12일 5281만원 수익률 -11.75%
 - 5월 16일 4492만원 수익률 -25.2%
 - 5월 25일 4910만원 수익률 -17.1%
 - 6월 02일 4910만원 수익률 -17.1%
 - 6월 20일 4130만원 수익률 -29.0% (종강)


## 1조
 ```github: https://github.com/ruripian/stock_analysis```
 - 선별종목 20220407: 대한항공, GS건설, 금호석유
 - 전략: 우선 관심기업 선정 후. 뉴스 키워드 빈도수 기반으로 앞으로 분석 예정
 - 05월 12일: 유가 데이터를 수집하여 각 날짜별 원유 가격 변동과 가격을 비교하여 Linear regression으로 얘측 금호석유 매수 수익률 0%
 - 06월 02일: 금호석유화학 1.02% 수익 증가

## 2조
 ```github: https://github.com/20191792/BigdataAndNLP```
  - 선별종목 20220407: 크래프톤, 대한항공, 현대자동차, 카카오페이(분석해보니 비추)
  - 전략: 해당 주식의 상위 1000개의 최신 기사를 추출하고 핵심키워드 뽑아 매수 여부 판단
  - 06월 02일: 기아차, 현대차, 한국항공우주 매수 및 매도 1.6% 수익

## 3조
 ```github: https://github.com/seominseok4834/bigdata-analytics```
  - 선별종목 20220407: 
  - 전략: 네이버 증권에서 제공하는 뉴스 검색을통해 검색 기사의 긍정, 부정, 중립 예측해서 몇개의 기사가 긍정 부정인지 파악하고 feature로 사용해서 sklearn을 이용해 학습을 진행
  - 06월 02일: 전 주 종가평균보다 높은 경우 매수 낮은경우 매수 하지 않음. 하지만 네이버의 경우 긍정 신호가 온적이 없어 매수하지 않음.

## 4조
 ```github:```
 - 선별종목 20220407: 대한항공, 현대자동차, 카카오페이(분석해보니 비추)
 - 전략: 상승시의 기사를 크롤링해 키워드 추출하고 해당 키워드와 유사한 키워드가 뉴스기사에 많이 나올 경우 매수하는 전략 (해외여행 키워드가 중요 --> 해외여행 키워드가 많이 나올경우 매수 진행) 
 - 05월 12일: 키워드의 검색 빈도가 많아질때 매수하고 적어질때 매도하는 방안, 검색량 평균 (52정도 일때 주가 상승경향) 대한항공 지켜보는 중
 - 06월 02일: 대한항공 -2%

## 5조
 ```github: https://github.com/YongJuDo/BigdataAndNLP```
 - 선별종목 20220407: 항공주 (대한항공)
 - 전략: 긍정키워드를 지정해두고 특정 섹터의 주식 중 긍정키우더의 빈도수를 10분간격으로 모니터링하여 매수하는 전략
 - 05월 12일: 전체 100개의 주가에 대해 호재키워드 악재키워드를 선정해 각 종목마다 호재 악재키워드 빈도수와 주가 등락율을 이용해 모델을 구현함.
 - 06월 02일: RIS를 적용한 RNN모델을 이용함, 대한항공, KODEX 200매수하여 -3.5%

## 6조 
 ```github: https://github.com/gudtjr2949/bigdata_analyze```
 - 선별종목 20220407: 위메이드, 넷마블, 현대차, SKT
 - 전략: 제목, 본문포함 핵심키워드 실시간 분석을 통한 투자 진행
 - 05월 12일: 키워드 빈도수가 많을 경우 주가가 상승하는 가설을 세운 후  위메이드  -26%
 - 06월 02일: RNN을 활용한 키워드 검색빈도 기반의 예측모델, 위메이드 -9% 종료


