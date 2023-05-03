# 5조 팜스토리 스마트팜 온도, 습도측정
# Smart_farm_plan1_DHT11_LED_contorl
## 구성원: 오상우, 윤현호, 박세린, 이병현, 권용만

### 개요
스마트팜의 기초인 외부 환경요소를 측정하는 것을 베이스로 잡았습니다.<br/>
DHT11은 온도와 습도를 측정할 수 있는 센서입니다.<br/>
이 센서로 값을 측정할 때 표시 방법으로는 LED를 점멸하는 것으로 표현하였습니다. 

### 사용한 재료들
라즈베리파이4 B MPU 소형 컴퓨터
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231491922-5f9f4808-c4a5-42e8-a3dc-6370f3bea3c4.jpg">
</p>

브레드보드, DHT11 센서, LED
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231492370-56f394e5-60eb-4138-8113-65c485773c79.jpg">
</p>
<br/>

### GPIO 세팅
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231508170-647953c9-4627-43f8-bf00-b93f5eca4d2b.png">
</p>
DHT11 - Vcc: 1_pin 3.3V / Data: 7_pin (GPIO_4) / Ground: 6_pin<br/>
LED - 11_pin (GPIO_17) / Ground: 14_pin
<br/>

### 사용한 SW요소들
Rasberry Pi OS Legacy, 파이썬 3.7 버전, 파이썬 관련 모듈(time / RPi.GPIO / Adafruit_DHT / 라즈베리 파이4의 칩셋명 BCM2711 추가)
<br/>

### 구현 영상
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231494597-672900d9-cf49-4a55-84aa-42b22413bb42.jpg">
</p>
https://www.youtube.com/watch?v=QqqlsFfRtMo
