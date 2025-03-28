---
title: "HDMapViewer(QGISPlugin)_1.0.0_Manual"
date: 2025-03-31 00:00:00 +0900
categories: [Manual]
tags: [HDmap_Viewer,QGIS,Plugin]
---

HDMapViewer(QGISPlugin)_1.0.0 매뉴얼 작성

## Description
---
'[HDmap_Viewer1.0](https://mobiltech-menual.github.io/posts/HDmapViewer/)'을 고도화하여 QGIS에서 사용할 수 있도록 Plugin으로 제작하여 'HDMapViewer(QGISPlugin)_1.0.0'를 배포.

### - 목적
---
* '[IN54004_[Replica City]HDmap Viewer](https://docs.google.com/presentation/d/1cXCXp2r6wglWB05iU4lxa1TjTjvtYQmPCafb36JI1w4/edit#slide=id.g32cb8f9b0dd_0_120)' 프로젝트 일환
 * HD-Map 제작시에 MMS취득 영상과 카카오 로드뷰를 확인
* 차선의 색상, 표지판종류 등 정성적 데이터 취득
* 취득한 데이터 검수

## Visuals
---
![Image](https://github.com/user-attachments/assets/a30ac2c8-7a2c-4654-94c1-777695447a28)

## Installation
---
HDmap_Viewer.zip의 압축을 풀어서 HDmapViewer.exe를 실행

## Usage
---
1. MMS_Viewer.exe를 실행한다.

2. [1. Mount Event1.txt] 버튼을 클릭한다.

3. event1.txt파일을 로드한다.

4. [CameraPlayer]버튼을 클릭한다.

5. 나타난 Image Video Viewer윈도우에서 Load Folders를 클릭한다.

6. camera01폴더를 지정한다.
    6.1. 'Enter target gpstime' 텍스트상자에서 검색할 gpstime을 입력한다.
    6.2. 'Enter timeset'텍스트 상자에 18(gpstime가산수치)을 입력한다.

    6.3. 01~05버튼을 누르면 카메라전환이된다.

    6.4. 재생구간을 조정하는 프로그레스바와 play/Pause버튼 배속버튼 <<10s,10s>>버튼으로 영상을 조작한다.

    6.5. 필요시, HistEQ 체크박스로 영상의 이퀄라이저를 평준화하여 판독에 용이하도록한다.

7. [4. Map Open]버튼을 클릭한다.

8. [3. Draw a driving route]를 클릭한다.

9. Vworld Map윈도우에서 Vworld에서 발급받은 API Key를 입력한다. [Vworld API발급방법](https://docs.google.com/document/d/1PDpejOfeFIY2ktEUiXRAA-JwTfd82PQ-ECly_Mtsn78/edit#heading=h.gjdgxs)

    9.1. 이 상태에서 동영상을 재생하면 지도에 위치가 표시된다.

    9.2. 이 맵에서 경로 주변을 클릭하면 영상플레이어가 해당 지점을 재생한다.

    9.3. [Open RoadView] 버튼을 누르면 해당지점의 kakao로드뷰가 실행된다.

## Support
---
GoogleChat : shinmyeongho@mobiltech.io

## Roadmap
---
1. js파일로 login관리
2. QGIS MapCanvas와 image_video_viewer 신호처리
3. Ubuntu용 패키징
4. GUI Qt5 대체하여 리팩토링
5. 배포용 Installer.exe 작성
6. 사용 Menual 정리
