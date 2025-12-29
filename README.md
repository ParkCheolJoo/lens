# 3D 렌즈 시뮬레이터 (볼록/오목) — GitHub Pages 배포용

이 저장소는 `index.html` 단일 페이지로 동작하는 Three.js 기반 3D 렌즈(볼록/오목) 광선 추적 시뮬레이터입니다.
GitHub Pages에 바로 올려 배포할 수 있도록 PWA(선택) 파일과 아이콘이 포함되어 있습니다.

## 포함 파일
- `index.html` : 본문 시뮬레이터
- `manifest.webmanifest` : (선택) 홈 화면 추가용 PWA 매니페스트
- `sw.js` : (선택) 오프라인 캐시(간단 cache-first)
- `assets/icons/icon-192.png`, `assets/icons/icon-512.png` : 앱 아이콘
- `assets/icons/favicon.svg` : 파비콘

## GitHub Pages 배포 방법 (웹에서 업로드)
1. GitHub에서 새 Repository 생성 (Public 권장)
2. 이 폴더 안의 파일/폴더를 **그대로** 업로드 (drag & drop 가능)
3. Repository → **Settings** → **Pages**
4. **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** / Folder: **/** (root) 선택 후 Save
5. Pages URL이 생성되면 접속하여 확인

## 팁
- 파일을 `docs/` 폴더 아래에 넣는 방식으로도 배포할 수 있지만, 현재 구성은 루트(`/`) 배포 기준입니다.
- 캐시가 남아 새 버전이 즉시 반영되지 않으면, 브라우저 강력 새로고침(Shift+Reload) 또는 캐시 삭제 후 확인하세요.
