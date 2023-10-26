# bronze

구성품목
라즈베리파이, 라즈베리파이 7인치 디스플레이, L298N 모터드라이버, 환기팬, 관수펌프, 온습도센서, 방수형 온도센서 및 모듈, LED드라이버 및 LED, 조도센서, 토양수분센서, 서보모터, 스마트팜 화분, 카메라


전원 공급
라즈베리파이의 전원공급을 위해서 5V 3A이상의 전원공급이 필요
환기팬, 관수펌프, LED의 사용을 위해 12V 3A의 전원공급이 필요


필요 라이브러리 설치

sudo pip3 install Adafruit_DHT // 온습도 센서 사용을 위한 라이브러리 설치
sudo pip3 install w1thermsensor // 스마트팜 수조의 수온센서 사용을 위한 라이브러리 설치
sudo apt-get install python3-pyqt5 // pyqt 설치
sudo apt-get install pyqt5-dev-tools 또는 sudo apt-get install qttools5-dev-tools // pyqt tools 설치



환경설정
sudo raspi-config - Interfaces - (SPI, I2c, Serial Port, 1-Wire) Enabled 필요

메인 실행파일
smartfarm_control_ui_camera.py 작동 시 아래의 파일이 함께 작동됨
test2.ui

어플리케이션의 메인화면 이미지 첨부를 위해
smartfarm_control_ui_camera.py 소스코드 내부의 smartfarm_ui클래스 내부 image_paths 경로 설정이 필요함(이미지 파일이 있는 경로)


