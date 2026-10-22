# LET IT FLOAT — 설치형 웹 앱 v0.7

- 기억 보관함의 `기록 백업` 버튼 및 JSON 내보내기 기능 제거
- PWA 설정 추가: 앱 이름, 홈 화면 아이콘, 독립 실행 모드, 기본 오프라인 캐시
- iPhone 홈 화면 아이콘 메타데이터 추가
- 기존 기능과 브라우저 localStorage 저장 방식 유지

## GitHub에 업데이트하기
저장소에 아래 파일들을 모두 업로드하거나 기존 파일을 덮어쓰세요:
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon-192.png`
- `icon-512.png`
- `apple-touch-icon.png`

GitHub 저장소의 **Add file → Upload files**에서 파일을 선택한 뒤 **Commit changes**를 누르세요. GitHub Pages가 갱신될 때까지 잠시 기다리면 됩니다.

## 핸드폰에 앱처럼 설치하기
- **iPhone:** Safari에서 GitHub Pages 주소 열기 → 공유 버튼 → `홈 화면에 추가` → 추가
- **Android:** Chrome에서 주소 열기 → 메뉴(⋮) → `앱 설치` 또는 `홈 화면에 추가`

이 버전은 설치형 웹 앱(PWA)이며, 아직 App Store / Google Play에 등록된 네이티브 앱은 아닙니다. 기록은 기기별 브라우저 저장 공간(localStorage)에 저장되며, 기기간 자동 동기화는 지원하지 않습니다.
