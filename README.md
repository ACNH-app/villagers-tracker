# ACNH Villager Tracker

모여봐요 동물의 숲 주민을 성격과 동물종 기준으로 분류해서 보고, 주민별 상세 정보와 개인 체크 상태를 기록하는 독립 정적 웹페이지입니다.

## 포함 기능

- 성격별/동물종별 그룹 보기
- 주민 이름 검색
- 주민 상세 정보 확인
- `위시 주민`, `섬 주민`, `캠핑장 방문`, `이사감`, `사진 선물 받음` 상태 체크
- 브라우저 `localStorage` 기반 로컬 저장
- GitHub Pages 배포 가능 구조

## 파일 구성

- `index.html`: 정적 페이지 진입점
- `styles.css`: 화면 스타일
- `app.js`: 데이터 로딩, 렌더링, 상태 저장
- `data/villagers.json`: 배포용 주민 스냅샷
- `assets/villagers/*.png`: 주민 이미지
- `.github/workflows/deploy-pages.yml`: GitHub Pages 배포 워크플로
- `SOURCE_NOTES.md`: 데이터/이미지 출처
- `CHECKLIST.md`: 제작 체크리스트

## 새 레포로 연결할 때

- 이 폴더 자체를 새 Git 저장소 루트로 사용하면 됩니다.
- GitHub에 새 저장소를 연결한 뒤 `main` 브랜치에 푸시하면 Pages 워크플로가 배포를 시작하도록 구성했습니다.
- 현재 포함된 `data/villagers.json`과 `assets/villagers/*.png`만으로도 바로 정적 배포가 가능합니다.
