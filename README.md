# DeadByDaylight_ProjectFiles
* 데드 바이 데이라이트 게임 모작 프로젝트입니다.
  
## 개요
* 게임: Dead By Daylight
* 작업 기간: 25.09.01 ~ 25.11.06
* 개발 인원: 4명

## 팀원
* 유호근: 맵 / 오브젝트 배치
* 정민수(팀장): 플레이어_생존자
* 김미진: 플레이어_살인마
* 모명준: 오브젝트 / 게임 플로우
  
## 기술 스택
* 설계 
### ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) | ![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)
* 개발
### ![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white) | ![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson)
* 관리
### ![Perforce Helix](https://img.shields.io/badge/-PERFORCE%20HELIX-00AEEF?style=for-the-badge&logo=Perforce&logoColor=white)

## 자료
* [PDF 자료](https://drive.google.com/file/d/1sK6pO1RPUcEy97MlkMlrmkZVO4wCyjhE/view?usp=drive_link, "구현 내용의 문서화 파일입니다.")

## 핵심 구현
### 1. 타일 배치
* 타일 조합으로 게임 맵 구성
* 레벨에 배치된 스포너로 타일 스폰
* 매 게임마다 맵 구성 변경
### 2. 오브젝트 배치
* 타일BP에 부착된 스포너를 통해 오브젝트 생성
* 가중치 시스템 도입으로 오브젝트 간 일정 거리 유지
* 매 게임마다 오브젝트 위치 변경
### 3. 라이팅    
* SkyLight의 CubeMap 변경을 통한 그림자 색 변경 -> 시야 확보 보조
* Volumetric Fog 적용과 타일 부착 조명의 시너지로 자연스러운 분위기 형성
* SpotLight를 통해 오브젝트 상태 전파
### 4. 사운드
* AmbientSound로 전용 테마와 환경음 구현
* 살인마 캐릭터에 부착된 Box Collision으로 생존자 추적 시 추적음악 재생

## 해당 프로젝트 파일은 에셋이 제외되어 플레이가 불가합니다!
