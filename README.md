# embeddedsystem-project
> 임베디드시스템 설계
> 조원: 박지훈, 박용준, 김용준, 아버스, 류가홍

# 1주차 
- [x] 팀 구성 및 주제 선정 
- [x] 주제 조사 및 계획 수립

![title](/images/header.png) 
![title](/images/face.jpg)


## 스마트 미러(smart mirror)
 - 일상 생활에서 사용하는 거울을 통해 인터페이스를 출력하거나, 여러가지 기능을 수행할 수 있는 IoT 디바이스
 - 스마트 미러는 자동차의 스마트 백미러에 처음 도입되었으며 이후 쇼핑, 피트니스, 의료 분야 등 다양한 분야에 접목됨
 - 얼굴인식 기능으로 스마트 미러가 사용자의 얼굴을 인식하여 사용자 정보와 일정등을 호출

## 주제선정 및 목적
      주제: smart mirror 
      smart mirror 통해 날시예보, 달력, 각종 정보 등을 인터페이스에 출력하고 제어하며 얼굴 인식, 음성 인식 기능을 추가한다

- 임베디드시스템 설계 프로젝트에서 라즈베리파이를 이용한 smart mirror 제작하여 얼굴 인식(Deep-learning), 음성 인식 기술을 이용하여 날씨(Weather Forcast API), 달력(Google calendar), 일정(Schedule), 지도(Google Map API) 등 정보를 제공을 목표로 함.

## smart mirror 작동 원리
 - 하드웨어part 에서 거울 형식의 모니터를 제작하여 거울에 모니터의 화면이 출력되게 합니다. 
   라즈베리파이와 웹서버의 실시간통신으로 작동을 하게 됩니다. 라즈베리파이에서는 ui를 개발하기 위해 pyqt 라이브러리를 사용하고 뉴스,날씨등의 다양한 정보등을 얻기 위해 구글사의        api를 활용합니다. 
  라즈베리파이에 라즈비안(OS)과 OpenCV를 설치, 파이썬(python)으로 라즈베리 파이 카메라를 사용하여 얼굴인식기능을 추가합니다. 개인의 얼굴을 학습시켜 각 사람별로 구별하도록 합니다.
  

![title](/images/operate.png)

## 준비물
1. 유리  
스크린을 표시하기 위해 필요

2. 반사필름  
반사된 유리에 필름을 부착하여 선명도와 가시성을 높이기 위해 필요

3. 유리 거치대  
유리와 모니터 혹은 테블릿을 거치하기 위함

4. 라즈베리파이 및 모듈  
라즈베리파이를 비롯한 usb hub, 각종 부품과 카메라 모듈

5. 모니터 혹은 테블릿pc  
라즈베리파이로 부터 출력된 스크린을 표시하기 위해 필요
            
6. LED Strip  
액자 옆면에 LED Strip을 붙여 밝기 조절

7. RPI 카메라  
얼굴인식을 위하여 카메라 장착


>참고 사이트
- https://jeongchul.tistory.com/
- https://blog.naver.com/fuls

***


# 2주차
- [x] 스마트 미러 하드웨어 구성품 논의 및 리스트 작성
- [x] 스마트 미러의 핵심인 거울 제작에 초점을 둠

## 구매 예정 리스트
### 1. 라즈베리파이 터치스크린 78,000원   
![title](/images/touchscreen.png)     
구매사이트: https://www.devicemart.co.kr/goods/view?no=1273487  

### 2. 이중거울 50,000원  
![title](/images/mirror.png)  
구매사이트: http://www.atostore.com/product/detail.html?product_no=63&cate_no=27&display_group=1  

### 3. 이중거울 or 하프미러필름     
투과율 & 반사율 측면에서 이중거울이 효율적이기에 이중거울을 사용할 예정

### 4. 검정시트지 5,500원      
![title](/images/black.png)   
구매사이트: http://jdsoo.co.kr/shop/shopdetail.html?branduid=76469&NaPm=ct%3Djhnlb567%7Cci%3Dcheckout%7Ctr%3Dppc%7Ctrx%3D%7Chk%3Dc56ccc5b0d4dd558be9bb22ce7d92fcd94ae7493   
빛의 산란을 방지

### 5. 썬팅공구종합세트 9,000원  
![title](/images/tool.png)  


## 추가 구매 예상 리스트
1. 각종공구
2. 제작틀  
(거울과 부품 수령 후 제작을 진행하며 상의하에 직접 틀제작 계획)

***

# 3주차 
- [x] 배부받은 라즈베리파이 구성품 리스트 작성
- [x] 3주차 강의를 통해 배운 기본 세팅

