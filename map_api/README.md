# Map API 

## 기능 구현

- Kakao Maps API를 활용한 지도 웹 서비스
- 현재 위치 : 사용자 현재 위치 기반 서비스 구현
- 목적지 : 대피소 위치 (재난대피소 API 호출)
- 재난 발생 지점 시각화 및 위험 반경 표시
- 반응형 웹 디자인 적용

## 주요 기능
- 실시간 위치 기반 or DB 기반 서비스 
- 대피소까지의 안전 도보 경로 안내(카카오맵)
- 실시간 재난 정보 시각화
- 취약계층 친화적 UI/UX

## 파일 설명
- `map_api.html`: 메인 지도 서비스 페이지
- `map_wide.html`: 확장 ver.
- `temp.html`: kakaomaps api 테스트 맵
- `shelter_temp.html`: 대피소api 시도(X)


## 사용 방법
1. 페이지 접속 시 현재 위치 정보 제공 동의(브라우저의 경우)
2. 지도에서 재난 발생 지역과 현 위치 간의 반경 확인
![스크린샷 2025-04-10 235848](https://github.com/user-attachments/assets/4478c251-b9b0-47ac-9ccd-ad798a8bb6b9)

3. 주변 대피소 및 시설 검색
![스크린샷 2025-04-10 235837](https://github.com/user-attachments/assets/2524d405-4c7f-47c8-aac8-1ad5e134d81e)

4. 원하는 위치까지의 경로 확인 
![스크린샷 2025-04-11 000119](https://github.com/user-attachments/assets/2c553f86-1fc0-4c44-99d8-4ac8227365f1)
