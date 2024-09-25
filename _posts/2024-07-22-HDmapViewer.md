---
title: "HDmap_Viewer1.0"
date: 2024-07-22 00:00:00 +0900
categories: [Manual]
tags: [HDmap_Viewer]
---

HDmap viewer 개발과 공유 및 원활한 배포

## Menual

[HDmap_Viewer1.0_READEME](https://docs.google.com/presentation/d/1OwfA6Q_a3zGi3iah04wsiR9ZaDEcFOwv/edit?usp=drive_link&ouid=110477335478538752374&rtpof=true&sd=true
)

## Description
HD-MAP 제작을 위해서 위치에 따른 카메라영상 판독을 목적으로 만들어 졌다. 궁극적으로는 QGIS와 같은 도화툴의 위치와 카메라영상을 Join하여 판독하는 것이다.

## Visuals
![MMS_Viewer](https://github.com/user-attachments/assets/ade34f9d-f9d6-4ca7-9cb0-e4a5e852b93b)

## Installation
HDmap_Viewer.zip의 압축을 풀어서 HDmapViewer.exe를 실행

## Usage
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
GoogleChat : shinmyeongho@mobiltech.io

## Roadmap
1. js파일로 login관리
2. QGIS MapCanvas와 image_video_viewer 신호처리
3. Ubuntu용 패키징
4. GUI Qt5 대체하여 리팩토링
5. 배포용 Installer.exe 작성
6. 사용 Menual 정리
