# 5조 팜스토리 스마트팜 Node-red
# Smart_farm_plan2 Node-red and dashboard
## 구성원: 오상우, 윤현호, 박세린, 이병현, 권용만

### 개요
<p align="center">
<img src="https://user-images.githubusercontent.com/61779129/235955407-ad1bf8b4-f61f-4aa4-857a-ab4fe219127b.png">
</p>
Node-red 프레임워크 개발도구를 사용하였습니다.<br/>
Node-red 위젯에서 각 센서와 하드웨어의 구체적인 기능을 구현하고 흐름도를 설정할 수 있습니다.<br/>
Node-red에서 dashboard 라이브러리를 설치하여 데이터를 폭넓게 활용이 가능합니다.<br/>
dashboard를 통하여 측정값을 시각화한 자료로 정리할 수 있습니다.<br/>
dashboard를 통하여 작동부전원을 제어할 수 있습니다.<br/>

### 사용한 재료들
라즈베리파이4 B 임베디드시스템
<p align="center">
<img src="">
</p>

브레드보드, DHT11 센서, LED
<p align="center">
<img src="">
</p>
<br/>

### GPIO 세팅
DHT11 - Vcc: 4_pin 5V / Data: 7_pin (GPIO_4) / Ground: 6_pin<br/>
LED_Yel - 11_pin (GPIO_17) / Ground: 9_pin<br/>
LED_Red - 12_pin (GPIO_18) / Ground: 14_pin
<br/>

### 사용한 SW요소들
Rasberry Pi OS Legacy, Nord-red 프레임워크 개발도구, dashboard 라이브러리
<br/>

### 구현 영상
<p align="center">
<img src="https://user-images.githubusercontent.com/130550405/231494597-672900d9-cf49-4a55-84aa-42b22413bb42.jpg">
</p>
https://www.youtube.com/watch?v=QqqlsFfRtMo
