### [K-water AI 경진대회] 수돗물 수요예측 AI 알고리즘 개발 <b>Task<b/>

2017~2020년 4년치의 한 시간 마다의 적산차 값이 training data set, 2021년 1년치의 적산차 값이 validation data set으로 주어지고 이를 활용하여 2022년의 상수원 수요 변화에 따라 달라지는 배수지의 적산차를 예측 과제이다. 

모델은 <code>N-Linear</code> model을 사용하였다. 

#### N-Linear 

LTSF(long-term time series forecasting) 과제에서 시간 순차성 정보는 예측에 있어 가장 중요한 역할을 하게 된다.
transformer의 경우 이런 시간 순차성 정보를 보존하기 위해 positional encoding 기법을 사용하지만 
multi-head attention, self-attention 적용 후 시간 순차성에 대한 정보 손실을 피할 수 없다. -> 장기 시계열 예측에 악영향
따라서 간단한 Linear 모델로 LTSF 과제에서 트랜스포머 이상의 성능을 보여준다.













