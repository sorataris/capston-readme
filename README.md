# 음성인식 기반의 스마트 룸
-capstone design work

-캡스톤 디자인을 진행하면서 제작하였습니다.


# 개발 환경
음성인식
1. 개발언어 : python,java
2. DB : Firebase
3. 사용 라이브러리: pytorch,kocrawl,kochat,Gtts,flask
4. 사용된 보드: raspberryPi4 8G

웹UI
1. 개발언어: JS,HTML5
2. 개발환경: Eclipse
3. DB: Firebase
4. 사용된 보드: raspberryPi4 8G

앱UI
1. 개발언어: JAVA
2. 개발환경: Android Studio
3. DB: Firebase

IoT장치

1. 개발언어: C
2. 개발환경: Arduino IDE
3. 사용된 보드:esp-8266
4. 연결된 센서: LED, 기어모터, PDLC 필름, 릴레이/ 추가예정: 빗물감지 센서, 조도 센서
5. DB: Firebase

# 센서 역할 설명
1. LED = 집에서 사용하는 전등
2. 기어모터 = 창문 open/close
3. PDLC 필름 = 블라인드 기능 On/Off
4. 빗물감지 센서 = 우천시 자동 개폐
5. 조도센서 = 어두울 시 자동 전등 킴
6. 릴레이 = PDLC 필름에 전원 On/Off -> Off시 필름이 불투명해진다. On시 필름이 투명해진다.

# 주요 기능
1. 음성인식을 통하여 미리 준비된 장치 제어
2. 음성인식으로 지역 날씨,미세먼지, 맛집추천 등 여러가지 기능 사용
3. 음성 명령 결과는 다시 음성으로 결과 출력
4. Flask서버를 사용하여 웹 페이지에서 UI화면으로 준비된 장치 제어
5. APP을 통하여 외부에서도 준비된 장치 제어 가능
6. 모니터에 반사필름을 붙혀 스마트 미러처럼 평상시에는 모니터, 화면 꺼질 시 거울로 활용가능

# 순서도
![image](https://user-images.githubusercontent.com/116625723/197709000-1c0cc604-158f-4b6b-95c6-52e84edbdb07.png)



# 웹 UI
![image](https://user-images.githubusercontent.com/116625723/197711735-dd8ba9d7-8f34-431b-8b1c-20fc55152ba7.png)

# 앱 UI
![image](https://user-images.githubusercontent.com/116625723/197711815-2b2f4adb-70b1-4633-bfe7-628af748e28c.png)

# 창문
![image](https://user-images.githubusercontent.com/116625723/197713225-ce28f60d-86d7-4727-b139-ca0865f16f49.png)


해당 프로젝트는 hyunwoongko님이 올리신 kochat-master와 kocrawl API를 사용하여 자연어처리를 개발하였습니다.
https://github.com/hyunwoongko/kochat

시연 영상
https://www.youtube.com/watch?v=PQNwRPd2rok&t=4s
