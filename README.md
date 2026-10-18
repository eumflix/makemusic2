# 나도 작곡가 (GitHub Pages 배포용)

- `index.html` : 나도 작곡가 본체 (QR 코드는 올려 둔 주소를 자동으로 사용)
- `eval.html`  : 평가용 (본체의 「📝 평가」 버튼이 이 파일로 연결돼요)
- `.nojekyll`  : GitHub Pages가 파일을 그대로 서빙하도록 하는 빈 파일

## 올리는 방법
1. 새 저장소를 만들고 이 폴더의 파일을 모두 올립니다 (.nojekyll 포함).
2. Settings → Pages → Branch: `main` / `(root)` → Save.
3. 잠시 뒤 `https://<계정>.github.io/<저장소>/` 로 접속됩니다.

## 알아둘 점
- VexFlow, 구글 폰트는 인터넷(CDN)에서 불러와요. 오프라인에서는 악보가 그려지지 않아요.
- 내보내기(wav·SVG·zip)는 일반 브라우저 다운로드로 저장돼요 (「파일로 저장」 누르기).
- 평가 제출은 claude.ai 전용 저장소를 쓰지 않아요. 결과는 「결과 복사하기」로 전달합니다.
- 작업 내용은 각 브라우저(localStorage)에 저장돼요.
