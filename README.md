# 아침 경제 브리핑 PWA

## 📁 파일 구성
- `index.html` — 메인 앱
- `manifest.json` — PWA 설정
- `sw.js` — 서비스 워커 (오프라인 지원)
- `icons/` — 앱 아이콘 폴더 (직접 추가 필요)

## 🚀 무료 배포 방법 (GitHub Pages)

### 1단계 — GitHub 계정 만들기
https://github.com 에서 무료 가입

### 2단계 — 새 저장소 만들기
- New repository 클릭
- 이름: `economy-app` (영문)
- Public 선택
- Create repository 클릭

### 3단계 — 파일 업로드
- Upload files 클릭
- index.html, manifest.json, sw.js 모두 업로드
- Commit changes 클릭

### 4단계 — GitHub Pages 활성화
- Settings → Pages
- Source: Deploy from a branch
- Branch: main / root
- Save 클릭

### 5단계 — 완료!
약 1~2분 후 아래 주소로 접속 가능:
https://[GitHub아이디].github.io/economy-app

## 📱 핸드폰 홈 화면에 추가하는 방법

### 안드로이드 (크롬)
1. 앱 주소로 접속
2. 주소창 오른쪽 메뉴(⋮) 탭
3. "홈 화면에 추가" 선택
4. "추가" 확인

### 아이폰 (사파리)
1. Safari로 앱 주소 접속
2. 하단 공유 버튼(□↑) 탭
3. "홈 화면에 추가" 선택
4. "추가" 확인

## 🎨 아이콘 추가 방법
icons 폴더에 아래 두 파일을 추가하면 앱 아이콘이 표시됩니다:
- icon-192.png (192×192px)
- icon-512.png (512×512px)

Canva (https://canva.com) 에서 무료로 만들 수 있습니다.

## ✅ 기능
- 실시간 환율 (USD, JPY, EUR, CNY → KRW)
- 실시간 금시세 (1돈, 1온스)
- 국내 증시 링크 (코스피, 코스닥)
- AI 경제 브리핑 (Claude API 기반)
- 홈 화면 앱 설치 지원
- 오프라인 캐시 지원
