# KU_DFC
# 딥러닝 기반 한국어/영어 문맥 감성 분석

# [작성자 정보]
고려대학교 디지털융합과정 인공지능과자연어처리<br>
유근영, 김동혁, 김세윤, 이호현<br>

# [데이터 정보]
네이버 영화평 감성 분석 데이터 NSMC(Naver Sentiment Movie Corpus), 출처:https://github.com/e9t/nsmc <br>
Friends 대본 데이터, 출처:http://doraemon.iis.sinica.edu.tw/emotionlines/download.html <br>

# [실험 환경 정보]
해당 실험은 Google Colab 환경에서 구축되고 구동되었음 <br>
해당 실험은 Pyhton 언어 및 텐서플로우 케라스 라이브러리로 작성되었음 <br>
해당 실험에 사용된 데이터는 Open Source이며, 해당 실험에서는 Google Drive Mounting을 통해서 데이터를 Loading했음 <br>
해당 실험은 비정형 자연어 데이터를 다루고 있어 영어 이외의 언어에 별도의 폰트 설정을 진행하였음 <br>

# [실험 목차]
초기 환경설정 <br>
비정형 데이터 구조 파악(X/Y) <br>
비정형 데이터 전처리 - NA, 불용어 <br>
비정형 데이터 토큰화 - 형태소 <br>
비정형 데이터 시각화 <br>
비정형 데이터의 정형화 - 인코딩 <br>
시퀀스 입력 - 원핫벡터 <br>
시퀀스 임베딩 - 덴스벡터 <br>
시퀀스 신경망 - LSTM <br>
학습 신경망 - FC <br>
목적 함수 - Binary Cross Entropy / Categorical Cross Entropy <br>
최적화 모델 - RMSProp / ADAMs <br>
모델 학습 <br>
최적 모델 선정 <br>
모델 테스트 <br>
테스트 성과 평가 - Accuracy / Precision / Recall / F1 Score <br>

# 감사합니다 <br>
