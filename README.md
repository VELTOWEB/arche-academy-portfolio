# ARCHE ACADEMY — VELTOWEB Portfolio Sample

아르케 입시학원(ARCHE ACADEMY)은 VELTOWEB의 교육 업종 웹사이트 제작 역량을 보여주기 위해 만든 **가상 입시학원 포트폴리오 프로젝트**입니다. 실제 학원, 실제 강사, 실제 학생 성적, 실제 설명회 일정이 아닙니다.

## 구성
- `index.html` — 홈
- `about.html` — 학원소개 / 가상 위치 정보
- `teachers.html` — 강사진 + 과목 필터
- `curriculum.html` — 학년/과목별 과정 필터
- `results.html` — 가상 성적 향상 사례
- `management.html` — 학습관리 시스템 UI
- `seminar.html` — 설명회 목록 + 데모 신청 모달
- `consultation.html` — 상담 데모 폼 + FAQ
- `assets/css/style.css` — 공통 디자인
- `assets/css/responsive.css` — 반응형
- `assets/js/data.js` — 반복 콘텐츠 데이터
- `assets/js/main.js` — 메뉴, 필터, 탭, 폼, 모달, 애니메이션

## 실행
빌드 과정이나 패키지 설치가 필요 없습니다. `index.html`을 직접 열거나 간단한 로컬 서버에서 확인할 수 있습니다.

```bash
python -m http.server 8080
```

브라우저에서 `http://localhost:8080` 접속.

## GitHub Pages 배포
1. 이 프로젝트의 파일 전체를 저장소 루트에 업로드합니다.
2. GitHub 저장소 `Settings → Pages`에서 배포 브랜치를 선택합니다.
3. 모든 내부 경로가 상대경로이므로 프로젝트 서브디렉터리에서도 동작하도록 구성했습니다.

## 데모 기능 주의
- 상담/설명회 폼은 실제 서버로 전송되지 않습니다.
- 개인정보를 LocalStorage에 저장하지 않습니다.
- 성적, 강사진, 학원 주소, 전화번호, 설명회 일정은 모두 포트폴리오용 가상 정보입니다.
