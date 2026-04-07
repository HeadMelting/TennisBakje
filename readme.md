# tennis_3d_io GitHub Pages

`assets/animated_joon.glb` 와 `assets/joon.mov`를 브라우저에서 확인하는 정적 페이지입니다.

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

> 참고: `.mov`는 브라우저별 호환성 차이가 있어 필요하면 `.mp4(H.264)` 파일도 함께 제공하세요.
