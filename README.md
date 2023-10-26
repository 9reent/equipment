# bronze

필요 라이브러리 설치

sudo pip3 install Adafruit_DHT // 온습도 센서 사용을 위한 라이브러리 설치
sudo pip3 install w1thermsensor // 스마트팜 수조의 수온센서 사용을 위한 라이브러리 설치
sudo apt-get install python3-pyqt5 // pyqt 설치
sudo apt-get install pyqt5-dev-tools 또는 sudo apt-get install qttools5-dev-tools // pyqt tools 설치



환경설정
sudo raspi-config - Interfaces - (SPI, I2c, Serial Port, 1-Wire) Enabled 필요
