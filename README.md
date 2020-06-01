# LANL_Earthquake_Prediction

LANL Earthquake Prediction 대회에 참가 했던 소스코드입니다. (https://www.kaggle.com/c/LANL-Earthquake-Prediction/)

1. 방대한 데이터를 효율적으로 다루기 위해서 데이터 15000만개에 대해 mean, std, min, max, kurtosis 등의 feature들을 새로운 input data 로 정의하였습니다. 

2. LSTM과 FC layer로 이루어진 간단한 model을 이용해 학습을 진행하였습니다.

3. 팀으로 참가하였고 최종적으로는 Fourier transform을 통한 feature와 LightGBM을 이용해 상위 22% 성적을 거두었습니다.