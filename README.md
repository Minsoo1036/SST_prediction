# SST_prediction
수온(sst) 예측 프로젝트
<br>
**Term Project**
<br>
Time Series Analysis - Fall 2019
<br>
<br>
주어진 자료는 2007년부터 2018년까지의 국내의 한 정점에서 시간별로 관측한 수온 자료(sst) 및 종관 기상관측소에서 관측한 기온(temp), 기압(pres), 강수량(rain), 습도(hum), 일조시간(sun_hr)이다. 아래 제시한 문제 서술을 읽고 이를 해결하기 위한 팀 프로젝트를 진행하여 12월 10일 수업시간에 팀별로 발표를 진행한다.
<br>
- **주어진 자료 중 2016~2018년은 매월 28,29,30,31일에 해당하는 일의 시간별 수온 관측값은 NA로 처리가 되어 있다.**
- 주어진 정보를 활용하여 NA로 처리된 값들을 예측하는 모형을 만들어 예측치를 산출하여라. 단, 예측 모형에 시계열적 특성을 반영한 모형이 포함되어야 한다.
- 2018년 12월 28일부터 31일에 해당하는 경우에는 과거 자료로 부터 예측만 가능하나 2016년, 2017년의 NA에 해당하는 수온은 과거 및 미래 자료를 활용할 수 있다. 또한, 2018년 12월 28일부터 31일의 경우에는 수온 외에 다른 기상 변수들의 값도 알려져 있지 않다.
- 2016년, 2017년 NA 값의 예측 시 과거 자료만 고려한 모형과 과거 자료 및 해당 시점의 미래 자료도 이용한 모형을 탐색하여 최종 제안하는 모형을 정하고 예측값을 산출하여라.
- 예측 모형을 선택하게 된 근거를 제시하여야 한다. (예를 들어, 주어진 자료를 훈련 및 검증 자료로 구분하여 평가한 결과를 포함해야 함.)
- 평가 지표는 RMSE로 함.

