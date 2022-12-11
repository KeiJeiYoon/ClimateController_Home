# Hass.io Add-on: Kocom Wallpad with RS485 

![Supports aarch64 Architecture][aarch64-shield] ![Supports amd64 Architecture][amd64-shield] ![Supports armhf Architecture][armhf-shield] ![Supports armv7 Architecture][armv7-shield] ![Supports i386 Architecture][i386-shield]

## About
Kocom Wallpad with RS485

## Installation

1. 홈어시스턴트의 [설정] > [애드온] > [애드온 스토어] 의 우측상단 점3개 메뉴 > [애드온 저장소 관리] https://github.com/KeiJeiYoon/ClimateController_Home 를 입력한 다음 [추가] 버튼을 클릭.
2. 애드온 스토어 중간쯤에서 "Kocom Wallpad with RS485" 클릭.
3. share/kocom_home/ 폴더에 있는 kocom.conf 파일을 환경에 맞게 수정.
4. VirtualBox를 통하기 때문에 VirtualBox 네트워크 설정에서 HomeAssistant 8123, MQTT 1883 의 포트 포워딩 규칙을 만든다.
5. MQTT의 로긴 : usernaem 과 password 를 넣는거로 설정했기 때문에 구성원에서 설정내용과 같이 사용자를 추가한다.
-------------------------------------------------------------------------------------
(2022.12.6 ) github 개설

[forum]: https://cafe.naver.com/koreassistant
[github]: https://github.com/kyet/kocom.py
[github]: https://github.com/clipman/kocom.py
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
