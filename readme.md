# tennis_3d_io GitHub Pages

`assets/{name}/animated.glb` 와 `assets/{name}/video.mp4`를 브라우저에서 확인하는 정적 페이지입니다.

## 로컬에서 테스트

브라우저 보안 정책(CORS) 때문에 파일을 직접 열지 말고 간단한 서버로 실행하세요.

```bash
cd tennis_3d_io
python3 -m http.server 8080
```

그 다음 `http://localhost:8080` 접속.

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소로 올립니다.
2. 저장소 Settings -> Pages 에서 배포 브랜치(예: `main`)와 폴더(`/ (root)`)를 선택합니다.
3. 배포 URL에서 `index.html`이 기본 페이지로 열립니다.

> 참고: 현재 `three.js`는 `assets/vendor/`의 로컬 모듈을 사용하므로 CDN 없이도 로컬호스트에서 동작합니다.

## 프로필(네비게이션) 추가 방법

상단 네비게이션에서 선택 가능한 목록은 `assets/profiles.json`을 읽어옵니다.

1. `assets/{name}/animated.glb`
2. `assets/{name}/video.mp4`
3. `assets/profiles.json`에 `{name}` 문자열 추가

예시:

```json
[
  "joon",
  "minsu"
]
```
