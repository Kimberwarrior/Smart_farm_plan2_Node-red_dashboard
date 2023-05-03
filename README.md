# 5조 팜스토리 스마트팜 Node-red
# Smart_farm_plan2 Node-red and dashboard
## 구성원: 오상우, 윤현호, 박세린, 이병현, 권용만

### 개요
Node-red 프레임워크 개발도구를 사용하였습니다.<br/>
Node-red 위젯에서 각 센서와 하드웨어의 구체적인 기능을 구현하고 흐름도를 설정할 수 있습니다.<br/>
Node-red에서 dashboard 라이브러리를 설치하여 데이터를 폭넓게 활용이 가능합니다.<br/>
dashboard를 통하여 측정값을 시각화한 자료로 정리할 수 있습니다.<br/>
dashboard를 통하여 작동부전원을 제어할 수 있습니다.<br/>

### 사용한 재료들
라즈베리파이4 B 임베디드시스템
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
DHT11 - Vcc: 4_pin 5V / Data: 7_pin (GPIO_4) / Ground: 6_pin<br/>
LED_Yel - 11_pin (GPIO_17) / Ground: 9_pin
LED_Red - 12_pin (GPIO_18) / Ground: 14_pin
<br/>

### 사용한 SW요소들
Rasberry Pi OS Legacy, 파이썬 3.7 버전, 파이썬 관련 모듈(time / RPi.GPIO / Adafruit_DHT / 라즈베리 파이4의 칩셋명 BCM2711 추가)
<br/>

### 구현 영상
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231494597-672900d9-cf49-4a55-84aa-42b22413bb42.jpg">
</p>
https://www.youtube.com/watch?v=QqqlsFfRtMo
