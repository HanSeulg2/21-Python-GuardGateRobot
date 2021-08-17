# Python-GuardGateRobot

- Language : Python 3.7.3
- OS : Debian Linux, Raspbian
- Tools : Thonny IDE 3.3.10 For Linux
- 라이브러리 : OpenCV 3.4.3

### 특징목록
![특징목록](https://user-images.githubusercontent.com/71927210/129692531-0f47ae58-2e3a-4411-8c50-69069f7741eb.png)

### 요구사항
![요구사항](https://user-images.githubusercontent.com/71927210/129692578-2db6b2ba-771d-40a4-8789-081cb9bb7b29.png)


### 4족보행 로봇
#### 유스케이스
![유스케이스](https://user-images.githubusercontent.com/71927210/129693664-14d55e45-32f5-48f3-bce1-1a21b56649a6.png)
#### 시스템 순차 다이어그램
![시스템 순차 다이어그램](https://user-images.githubusercontent.com/71927210/129693712-5cfd67fd-8d4e-43ca-8060-c7b00ad46a0f.png)
#### 통신 다이어그램
![통신다이어그램](https://user-images.githubusercontent.com/71927210/129693906-1240a73b-356b-4560-9b47-e63f70dacfe8.png)
#### 결과
![4족보행로봇](https://user-images.githubusercontent.com/71927210/129693104-f20837da-f5a5-44ad-abd2-3001ccf81ed3.png) 
- 4개의 서보모터를 활용하여 바퀴를 구성하였다.
- LED를 부착하여 주행시 점등이 되도록 구성하였다.
- 브레드보드에 연결된 버튼을 활용하여 로봇을 주행할 수 있도록 구성하였다.
- 각 대각선 방향의 바퀴가 쌍으로 앞,뒤로 움직이게 구성하여 정면으로 주행할 수 있다.
### 차단기
![차단기](https://user-images.githubusercontent.com/71927210/129693215-e665a426-35ab-43c0-8445-70b8b6644c24.png)
- 차단기는 서보모터를 활용하여 구성하였다.
- 차단기에 웹캠을 설치하여 지속적인 촬영이 가능하도록 구성하였다.
- 웹캠을 통해 움직임이 감지되면 차단기가 열리고, 일정시간 움직임이 감지되지 않으면 차단기가 닫히도록 구성하였다.
- 차단기는 사용자가 제어할 필요없이 자동으로 개폐가 가능하다.
