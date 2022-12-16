라즈베리파일을 이용한 이미지 러닝 훈련 소스코드

<박준하>-자료조사, 문서작업, 코딩
카메라가 인식하기 위한 이미지 찾기
-유리병, 플라스틱
얼굴 인식 Test 코드 학습
-얼굴인식 Test 코드 – OpenCV : https://stickode.tistory.com/197

이미지 xml 파일 만들기
-유리병
gibhub에서 LabelImg를 다운받아 사용

<이환규>-자료조사, 디자인, 코딩
카메라가 인식하기 위한 이미지 찾기
-캔, 플라스틱

라즈베리파이 환경 구축
-라즈베리파이에 카메라와 Tensorflow 설치
:: 코드
~ $ git clone https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-
on-Android-and-Raspberry-Pi.git
-TFLite-webcam 실행

-사용환경 만들어주기
-source project_env/bin/activate
  (raspberrypi% -> (project_env)rasberryip%로 변한 것을 확인하면 됨)
-python으로 된 webcam을 미리 다운로드 한 모델을 이용하여 작동
 -python TFLite_detection_webcam.py --modeldir=test_model
  (해석: python으로 작성된 웹캠 파일을 "test_model(임시파일명)"을 사용하여 작동시킬 것이다.)
  

<임소정>-지료조사, 문서작업, 디자인
라즈베리파이 환경 구축
-프로그램을 설치하기 위해 카메라 모듈과 OpenCV 설치
-카메라 모듈 설정 및 변환
-OpenCV 설치 후 소스코드 받아 컴파일 작업

이미지 xml 파일 만들기
-캔
gibhub에서 LabelImg를 다운받아 사용

<임은서>-자료조사, 디자인, 모형제작
컨베이어 벨트 제작
-레고마인드스톰 EV3로 'LEGO education'사이트에서 제공해주는 컨베이어 벨트 조립 설명서를 보고 제작
-컨베이어 벨트를 작동시키기 위한 레고마인드스톰 소프트웨어를 다운받아 로봇과 컴퓨터를 선으로 연결하여 코드 직접 실행 

이미지 xml 파일 만들기
-플라스틱
gibhub에서 LabelImg를 다운받아 사용

[응용사례]
시각장애인을 인식하는 모델 만들기
-지팡이 이미지와 휠체어 이미지를 구분한다
-이미지는 같은 방법으로 xml파일을 만든다

활용방안
- 횡단보도에서 시각장애인용 신호버튼을 눌러주는 게 아닌 카메라로 시각장애인(지팡이, 휠체어)을 
  인식해 신호를 바꿔준다
