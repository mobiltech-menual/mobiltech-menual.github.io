---
title: "HDMapViewer(QGISPlugin)_1.0.0[Manual]"
date: 2025-03-28 00:00:00 +0900
categories: [Manual, HDMapViewer]
tags: [HDmap_Viewer,QGIS,Plugin,Manual]
---

HDMapViewer(QGISPlugin)_1.0.0 (Manual)

## Installation
***
#### 1. [HDMapViewer_윈도우_.zip](https://10.1.1.12/shinmyeongho/hdmapviewer1.0.0_qgispluginforwindows/-/blob/main/HDMapViewer_%EC%9C%88%EB%8F%84%EC%9A%B0_.zip) 다운로드

   
#### 2. QGIS 실행

   
#### 3. 메뉴바 - 플러그인 - 플러그인 관리 및 설치

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/3.png?raw=true)

#### 4. ZIP 파일에서 설치 - 다운받은 HDMapViewer_윈도우_.zip 경로지정 - 플러그인설치

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/4.png?raw=true)

#### 5. 보안경고 - 예

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/5.png?raw=true)  

#### 6. 설치 성공

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/6.png?raw=true)
- 설치 버전 확인 가능

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/6-1.png?raw=true)

## Manual
***
### 인터페이스
***
![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/%EC%9D%B81.png?raw=true)

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/%EC%9D%B82.png?raw=true)

* QGIS Toolbar button

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/inteface1.png?raw=true)

* mainPlugin 위젯

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/inteface2.png?raw=true)

* VideoController 위젯

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/inteface3.png?raw=true)

* API-key 등록 위젯

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)/inteface4.png?raw=true)
### 1. 프로젝트 좌표계 설정
* (현재 버전에서는 프로젝트 좌표계가 32652로 설정되어야 함)
![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/1-1.png?raw=true)
* 적용 안되어있을 시, 위 이미지의 좌표계를 클릭하여 아래와 같이 설정
![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/1-2.png?raw=true)
![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/1-2.png?raw=true)
### 2. 실행
* QGIS Toolbar에서 아이콘 클릭하여 플러그인 실행
  
![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/2-1.png?raw=true)

### 3. 카카오 API관련
#### a. 카카오 처음 사용시 API등록 ([API 발급방법 Link](https://mobiltech-menual.github.io/posts/kakaoAPI%EB%B0%9C%EA%B8%89/) 참조)
* 등록하기 (※한번만 등록하면 된다.)

![Image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-1.png?raw=true)
* 새로고침((※한번 등록하면 그 후 불필요.)

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-2.png?raw=true)

#### b. 카카오 관련 기능
+ ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-3,7.png?raw=true)우클릭 컨텍스트메뉴

ㄴ ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-4.png?raw=true) QGIS 맵캔버스에  ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-5.png?raw=true) 마크 on/off

ㄴ ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-6.png?raw=true)  QGIS 맵캔버스의 뷰포트를 카카오 로드뷰 지점으로 이동
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/3-3,7.png?raw=true) 토글시 로드뷰 화면 on/off

### 4. MMS Camera 영상 관련
#### a. 비디오 컨트롤러
![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4a-1.png?raw=true)
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4a-2.png?raw=true)버튼들은 main위젯과 동일한 작동으로 동기화됨

#### b. MMS 영상 데이터 로드
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4b-1.png?raw=true)클릭 후 event1.txt 지정

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4b-2.png?raw=true)
* '01_camera'폴더는 자동으로 로드되며, 실패 시 수동으로 지정 가능
* 로딩 화면

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4b-3.png?raw=true)
* load된 모습

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4b-4.png?raw=true)

#### c. 영상플레이어 기능
* 재생바와 버튼으로 (재생/정지/배속/3초 전,후/재생로딩바조작/재생시간표시/재생중인청크표시)

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4c-1.png?raw=true)
![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4c-2.png?raw=true)

#### d. HistEQ 기능
* on / off 비교

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4d-1.png?raw=true)

#### e. gpstime검색으로 영상 로드
* gpstime입력 / timeset에는 표준시 가감

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4e-1.png?raw=true)

#### f. 카메라 버튼
* 카메라 버튼 조작하여 해당 방향의 MMS카메라 영상 호출

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4f-1.png?raw=true)
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4f-2,4k-1.png?raw=true)호출시 QGIS 맵캔버스에 빨간색 원뿔로 바라보는 방향이 표시된다.

#### g. 위젯 도킹 on/off
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4g-1.png?raw=true)버튼으로 위젯 도킹모드 on/off

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4g-2.png?raw=true)

#### h. View on/off
 * ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4h-3.png?raw=true)버튼을 토글하여 각 view를 on/off 가능하다.

#### i. 뷰 가로, 세로 정렬
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4i-1.png?raw=true)버튼으로 가로,세로 정렬

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4i-2.png?raw=true)

#### j. 경로 그리기
 * event1.txt 로드 되어 있어야 함. 
 * MMS버튼의 우클릭 컨텍스트 메뉴 - 경로그리기 or 폴더경로그리기

 ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4j-1.png?raw=true)
 
 * 아래 이미지 처럼 event1.txt와 카메라 청크를 어떻게 뽑느냐에 따라서 경로차이가 발생한다. 로드된 영상은 초록색 경로라고 생각하면 된다.
 ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4j-2.png?raw=true)
 
#### k. MMS 마크 on/off
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4f-2,4k-1.png?raw=true)QGIS 맵캔버스에서 MMS 마크를 on/off 한다.

#### l. 현재 위치로
* 현재 재생중인 시점의 위치로 QGIS 맵캔버스의 뷰포트가 이동한다.

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4l-1.png?raw=true)

#### m. MMS추적
* on일 경우 맵캔버스의 뷰포트가 재생중인 영상의 위치좌표를 실시간으로 따라다닌다.

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4m-1.png?raw=true)

#### n. VideoController on/off
* VideoController위젯을 on/off한다.

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/4n-1.png?raw=true)

### 5. 공통
#### a. 지도 위치 선택 기능
* ![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/5-1.png?raw=true)버튼 클릭 후 맵캔버스에서 드래그앤드롭으로 좌표와 방향을 취득.

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/5-2.png?raw=true)
* 취득한 좌표와 방향으로 로드뷰와 MMS영상을 갱신

![image](https://github.com/mobiltech-menual/mobiltech-menual.github.io/blob/main/assets/img/post/2025-03-31-HDMapViewer(QGISPlugin)Manual/5-3.png?raw=true)

## Support
***
GoogleChat : shinmyeongho@mobiltech.io
