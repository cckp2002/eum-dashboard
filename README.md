# 이음 E-UM 자료 대시보드

정적 사이트입니다(서버·빌드 없음). 프로그램·프롬프트·안내서·사례집·보고서로 연결합니다.

- `index.html` 대시보드 / `viewer.html?doc=manual|casebook|report` e북 뷰어
- `config.js` 문구·링크·쪽수 (수정은 이 파일만)
- `pdf/` PDF 원문, `vendor/` PDF.js 3.11.174 · StPageFlip 2.0.7 (둘 다 무료 MIT/Apache)

## 미리보기
폴더에서 `npx http-server . -p 5174` 후 http://127.0.0.1:5174/ (파일을 더블클릭하면 PDF가 안 열립니다).

## 게시 (GitHub Pages)
새 저장소(예: `eum-dashboard`)에 이 폴더 내용을 올리고 Settings → Pages → Branch `main` / root.
주소 예: `https://cckp2002.github.io/eum-dashboard/`

## 문서 교체
같은 이름으로 `pdf/`의 파일을 덮어쓰고, 쪽수가 바뀌면 `config.js`의 `pages`를 고칩니다.
