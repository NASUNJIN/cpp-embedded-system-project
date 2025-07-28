# 임베디드 시스템 기초 프로젝트 - 스마트 버스정류장 &amp; 버스

<img width="4400" height="2493" alt="임베디드" src="https://github.com/user-attachments/assets/bfb83074-9137-4cb6-978a-d0e0d374366e" />

<br />

### 영상링크
https://www.notion.so/Smart-Bus-Stop-14fab48f8bca80509fbacfb49c0def43?source=copy_link

<br />

## 프로젝트 소개

- 임베디드시스템 기말 프로젝트
- 시각장애인을 위한 버스 예약 시스템
- 버스 정류장에 존재하는 조이스틱으로 원하는 버스를 예약하면, 버스정류장과 가장 가까운 해당 버스의 기사님에게 버스 정류장을 알려 줌

<br />

## 주요 기능
- 버스 정류장에 있는 예약 시스템을 통해 원하는 버스를 예약할 수 있음 (PIR 센서를 통해 사람 감지)
    - 시각장애인도 사용할 수 있게, 해당 시스템은 조이스틱으로만 작동하며, 버스 번호와 정보는 LCD와 스피커를 통해 알려 줌.
    - 버스 예약이 완료될 경우, 해당 버스 기사님에게 예약 정보(예약된 버스정류장)를 알려 줌.
- 버스 앞문이 열릴 경우, 스피커를 통해 해당 버스 번호를 알려 줌.
- 버스 뒷문이 열리거나 닫기는 경우, 초음파 센서를 통해 버스 뒷문 끼임 방지. 
만약, 끼임이 발생하였을 경우 뒷문이 다시 열림
- 버스 정류장에 있는 흡연감지센서(MQ-2)를 통해 흡연 여부를 파악하고, 흡연을 할 경우 스피커를 통해 금연 구역이라고 알림

<br />

## 요약
<img width="4400" height="2493" alt="스크린샷 2025-07-24 오전 10 24 14" src="https://github.com/user-attachments/assets/95b7577d-16ed-4c52-806f-b4bf75286186" />

<br/>

### 버스 제어

|<img width="638" height="357" alt="스크린샷 2025-07-24 오전 10 25 52" src="https://github.com/user-attachments/assets/327e4ae9-144e-4b23-9b2d-f72ba399a1d2" />|<img width="637" height="357" alt="스크린샷 2025-07-24 오전 10 26 21" src="https://github.com/user-attachments/assets/0baec4e2-dda1-4708-9ce4-a0e8aabcf600" />|
|--|--|


|![LED_제어](https://github.com/user-attachments/assets/6fa782e5-90fd-4a61-9fb6-460b17674f70)|![앞문제어](https://github.com/user-attachments/assets/978fbc7b-002a-487e-9a38-a67949e1506a)|![뒷문제어](https://github.com/user-attachments/assets/2cfeab14-15b2-4e17-8085-499b7493863c)|
|---|---|---|
|LED 제어|앞문 제어|뒷문 제어|

<br />

### 버스 앞문
|<img width="638" height="359" alt="스크린샷 2025-07-24 오전 10![Uploading 스크린샷 2025-07-24 오전 10.58.58.png…]()58 38" src="https://github.com/user-attachments/assets/469aebff-2158-4fed-af3d-e7460aa2c1fc" />|<img width="637" height="357" alt="스크린샷 2025-07-24 오전 10 59 22" src="https://github.com/user-attachments/assets/31273b98-b09f-4760-b86d-f9fe3a7d9e20" />|
|--|--|

[버스번호 출력]
<br />
![버스번호_출력](https://github.com/user-attachments/assets/b3d90673-66a3-4969-905a-321950a98c14)

<br />

### 버스 뒷문
|<img width="640" height="360" alt="스크린샷 2025-07-24 오전 11 03 01" src="https://github.com/user-attachments/assets/2aab94c2-fee2-4926-9033-dfbc3528996a" />|<img width="638" height="359" alt="스크린샷 2025-07-24 오전 11 03 18" src="https://github.com/user-attachments/assets/7b925526-9f2f-4017-bf6a-de0f594221da" />|
|--|--|

[버스 예약 정보 전달]
<br />
![버스_예약정보_전달](https://github.com/user-attachments/assets/1434581e-ce73-4098-b165-035d32a06c67)


<br />

### 버스 예약
|<img width="642" height="359" alt="스크린샷 2025-07-24 오전 11 15 09" src="https://github.com/user-attachments/assets/85b861ce-af71-48d6-a550-bfbec0c39c6a" />|<img width="640" height="360" alt="스크린샷 2025-07-24 오전 11 15 29" src="https://github.com/user-attachments/assets/0e42b5b7-5856-40d4-95ba-dfa02b92f6a6" />|
|--|--|

[버스 예약]
|![버스_예약_앞](https://github.com/user-attachments/assets/f9f0d05c-82d9-466d-a5b5-235ce2d0951b)|![버스_예약_뒤](https://github.com/user-attachments/assets/9fa5f66d-d931-4e9e-b0bb-83b62ee0514a)|
|--|--|
|버스예약 1|버스예약 2|

<br />

### 흡연 감지
|<img width="638" height="357" alt="스크린샷 2025-07-28 오후 9 36 46" src="https://github.com/user-attachments/assets/27cd7762-a395-48d3-9c98-2afdbffb80cd" />|<img width="638" height="358" alt="스크린샷 2025-07-28 오후 9 37 02" src="https://github.com/user-attachments/assets/efea5cc8-da8e-4972-ae29-828935133cec" />|
|--|--|

[흡연감지]
<br />
![흡연_감지](https://github.com/user-attachments/assets/e71316d6-2e3a-46eb-b3de-9baef014fd18)


<br />

## 파트
- 버스 뒷문, 문끼임 방지
- 예약 시스템 (I2C 통신)
- 뒷문 조작 (UART 통신)
