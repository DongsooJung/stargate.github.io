# NAVER MAP API 현재 위치 수집 프로그램 개발 기록

## 작업 정보

* 작업일: 2026-03-14
* 프로젝트: STARGATE 홈페이지 - 위치정보 수집 기능 추가
* 브랜치: claude/naver-map-current-location-011CUdSffiyKPq4XKEXhEnvz

## 완료된 작업

1. location.html 생성 - NAVER Map API를 활용한 위치 추적 웹 애플리케이션
1. index.html 네비게이션 메뉴에 "위치정보" 링크 추가 (데스크톱/모바일)
1. NAVER Cloud Platform에서 Maps API 이용 신청 및 Application 등록
1. Client ID (q5nnmmlvz8) 발급 완료
1. location.html의 YOUR_CLIENT_ID를 실제 Client ID로 교체
1. Git 커밋 및 푸시 완료

## 주요 기능

* 현재 위치 가져오기: 브라우저 Geolocation API로 실시간 위치 수집 (위도, 경도, 정확도, 고도, 속도, 방향)
* 실시간 위치 추적: 위치 변화를 실시간 모니터링하는 추적 모드 (시작/중지 토글)
* NAVER Map 연동: 현재 위치를 지도에 마커로 표시, 정확도 범위를 원으로 시각화, 자동 지도 중심 이동
* 위치 기록 저장: localStorage를 사용한 위치 히스토리 저장, 수집된 위치 데이터 목록 표시
* 반응형 디자인: 모바일/데스크톱 대응, 그라디언트 UI

## NAVER Cloud Platform 설정 정보

* 콘솔: https://console.ncloud.com/maps/application
* Application 이름: STARGATE
* Client ID: q5nnmmlvz8
* 등록된 API: Directions 5, Geocoding, Reverse Geocoding, Directions 15, Static Map, Dynamic Map
* Web 서비스 URL: http://stargate11.com

## 접속 방법

* 메인 페이지에서 "위치정보" 메뉴 클릭
* 또는 직접 /location.html 접속
* GitHub Pages로 배포됨

## 참고 링크

* NAVER Maps JavaScript API v3: https://navermaps.github.io/maps.js.ncp/
* NAVER Cloud Platform Maps 콘솔: https://console.ncloud.com/maps/application
* Client ID 발급 가이드: https://navermaps.github.io/maps.js.ncp/docs/tutorial-1-Getting-Client-ID.html
