
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

## 라즈베리파이 키트 부품 조사
[작성 리스트](https://github.com/kanyevelvet/embedded-kit)  

## 스마트미러 구성도
![title](/images/mir.png) 

## 구매한 부품
1. 라즈베리파이 공식 7인치 터치스크린. 가격: 78,000원. 수량: 1개
2. 소형 스틱 콘텐서마이크. 가격: 5,500원. 수량: 1개
3. USB to 3.5mm AUX(이어폰 마이크 변환 젠터 케이블 오디오 연결잭). 가격: 5,500원. 수량: 1개
4. 자동차 썬팅필름 DIY 썬팅도구(우레탄헤라). 가격: 3,600원. 수량: 1개
5. 검정 단색시트지. 가격: 2,700원. 수량: 1개
6. 고급형 하프미러 4T A4사이즈. 가격: 55,000원. 수량: 1개

>총 주문 금액: 181,200원(배송비 포함)

## 라즈베리파이 라즈비안설치

- micro sd카드 포맷
1) https://www.sdcard.org/downloads/formatter/eula_windows/index.html 접속
2) SDCardFormatter.zip 다운로드 
3) 압축 해제 후 SD Card Formatter 실행 
4) sd카드를 삽입 
5) Select card 에서 sd카드 드라이브를 선택후 Format버튼을 눌러 초기화 실행
![title](/images/sdformat1.PNG) 
![title](/images/sdformat2.PNG) 

- 라즈비안 파일 다운로드
1) https://www.raspberrypi.org/downloads/raspberry-pi-os/ 접속
2) Raspberry Pi OS (32-bit) with desktop and recommended software 다운로드
3) 압축 해제 -> 이미지 파일 생성
![title](/images/rasbian1.PNG) 
![title](/images/rasbian2.PNG) 

- Win32DiskImager
1) https://sourceforge.net/projects/win32diskimager/files/latest/download 접속
2) 다운로드 후 실행
3) 실행창에서 폴더 클릭 - 라즈비안 이미지 파일 생성 - Write 클릭
![title](/images/win1.PNG) 

- 라즈베리파이에 라즈비안OS 설치
1) sd카드의 boot(D:)에 들어가 ssh파일 만들기
![title](/images/ssh1.PNG) 
![title](/images/ssh2.PNG) 
2) sd카드에 이미지 파일을 받은 후 라즈베리파이에 삽입
3) 전원을 인가하여 컴퓨터와 라즈베리파이를 연결
4) https://www.putty.org/ 접속하여 putty를 다운로드 (putty를 설치하여 ssh로 통신하기)
5) 실행 후 host name에 공유기의 ip 입력 - open 버튼 클릭
![title](/images/ssh3.PNG) 
6) cmd 창의 login에 pi, password에 raspberry 입력, 연결 확인
![title](/images/ssh4.PNG) 
![title](/images/ssh5.PNG) 
7) https://www.realvnc.com/en/connect/download/viewer/ 접속
8) RealVnc 다운로드 (데스크톱에서 가상으로 화면을 띄우는 방법)
9) 실행 후 입력했던 ip주소와 id, password 입력 - ok버튼 클릭 
10) 라즈베리파이 운영체제 화면 생성
![title](/images/ssh6.PNG) 

***

## 4주차
- OpenCV에 대해 조사

## OpenCV란?
![title](/images/opencv.png)
- OpenCV (Open Source Computer Vision Library)는 오픈 소스 컴퓨터 비전 및 머신 러닝 소프트웨어 라이브러리입니다. OpenCV는 컴퓨터 비전 애플리케이션을위한 공통 인프라를 제공하고 상용 제품에서 기계 인식의 사용을 가속화하기 위해 구축되었습니다.

- 라이브러리에는 2,500 개 이상의 최적화 된 알고리즘이 있으며, 여기에는 클래식 및 최첨단 컴퓨터 비전과 기계 학습 알고리즘의 포괄적 인 집합이 포함됩니다. 이러한 알고리즘은 얼굴을 감지 및 인식하고, 물체를 식별하고, 비디오에서 인간의 행동을 분류하고, 카메라 움직임을 추적하고, 움직이는 물체를 추적하고, 물체의 3D 모델을 추출하고, 스테레오 카메라에서 3D 포인트 클라우드를 생성하고, 이미지를 함께 연결하여 고해상도를 생성하는 데 사용할 수 있습니다. 전체 장면의 이미지, 이미지 데이터베이스에서 유사한 이미지 찾기, 플래시를 사용하여 촬영 한 이미지에서 적목 현상 제거, 눈의 움직임 추적, 풍경 인식 및 증강 현실 오버레이를위한 마커 설정 등이 있습니다.

- C ++, Python, Java 및 MATLAB 인터페이스가 있으며 Windows, Linux,  Android  및 Mac OS를 지원합니다. openCV는 주로 실시간 비전 애플리케이션에 기울이며 사용 가능한 경우 MMX 및 SSE 명령을 활용합니다. 모든 기능을 갖춘  CUDA 및  OpenCL  인터페이스가 현재 활발하게 개발되고 있습니다.

## 주요 알고리즘
1. 이진화(binarization)
2. 노이즈 제거
3. 외곽선 검출(edge detection)
4. 패턴인식
5. 기계학습(machine learning)
6. ROI(Region Of Interest) 설정
7. 이미지 변환(image warping)
8. 하드웨어 가속

- 출처 : https://opencv.org/

## OpenCV를 통한 스마트미러 기능 사용

![title](/images/opencv2.jpg)
- OpenCV를 통해 얼굴인식 하는 과정
1. OpenCV 필수 구성요소 설치
2. OpenCV 용 Pyhton가상 환경 구성
3. OpenCV 환경설정
4. OpenCV 컴파일
5. Pip로 필요 기본모듈 설치
6. dataset에 본인의 사진 찍어 넣기

- 출처 : https://blog.naver.com/dtvdtv2/221958738257

***

## 5주차
- 라즈베리파이에 매직미러 설치 단계

## 라즈베리파이 설치 · 세팅

![title](/images/Raset1.png.PNG)![title](/images/Raset2.png.PNG)![title](/images/Raset3.png.PNG)
1. 준비물 : 마이크로 SD카드, 마이크로 SD카드 리더기, USB 소형 마이크, AUX 3.5mm 오디오 단자, 라즈베리파이, 키보드, 마우스, 마이크로 USB 어댑터(2A 이상)
