# Google ML 부트캠프 협력 실무 프로젝트

## 요일별 학습 주제
* 월: 인공신경망 모델의 구조 이론
* 화: 인공신경망 모델의 구조 및 동작원리와 최적화 이론의 이해
* 수: 인공신경망 CNN 아키텍처
* 목: 실시간 객체탐지 모델
* 금: 딥러닝을 활용한 자연어처리

* 월: 생성형 인공지능 모델 - GAN, VAE
* 화: 실시간 객체 탐지를 위한 인공지능 플랫폼(Roboflow, Ultralytics, LangChain) 활용
* 수: 허깅페이스 트랜스포머 모델 사용하기
* 목: ChatGPT(또는 Gemini) API를 활용한 서비스 개발
* 금: 자바 스프링 부트 프로젝트와 파이썬 AI 프로젝트 연결하기


## 참고 URL
* 자바와 파이썬 AI 서버 연결: https://github.com/hjk7902/java2ai
* 인공지능: https://github.com/hjk7902/ai
* YOLOv3 논문: https://arxiv.org/pdf/1804.02767
* 윈도우 10에서 GPU 사용하기: https://javaspecialist.co.kr/board/1244
* 텐서플로우 GPU 사용 가이드: https://www.tensorflow.org/install/gpu?hl=ko
* GoogLeNet논문: https://arxiv.org/pdf/1409.4842
* 


## 실시간 객체탐지 예제코드를 실행하려면 tensowflow 2.14 이하 버전이 있어야 합니다.
아나콘다를 2022년 버전을 설치하거나... 다음 절차를 따르세요.

1. 가상환경 추가
conda create -n tf2.14 python=3.11
conda activate tf2.14

2. 주피터노트북 ipykernel 추가
pip install ipykernel
ipython kernel install --name=tf.214 --user

3. 라이브러리 설치
python -m pip install pip==23.0   <- pip 버전을 다운그래이드 해야 텐서플로우 2.14 설치 가능
pip install tensorflow==2.14 
pip install opencv-python scikit-learn pandas nltk ipywidgets tqdm datasets
