# Pick Me! 👀

커스텀 CAPTCHA 스타일 이미지를 만드는 브라우저 기반 미니 웹툴입니다.

## 주요 기능
- 2x2 / 3x2 / 3x3 레이아웃 선택
- 각 타일별 이미지 업로드
- 이미지 위치 및 확대 조절
- 타일 순서 변경
- 큰 타이틀 / 상세 문구 편집
- 체크 아이콘 스타일 선택
- CAPTCHA 헤더 컬러 변경
- PNG 저장
- 모바일 미리보기 자동 축소

## 특징
- 서버 저장 없음
- 로그인 없음
- 업로드한 이미지는 브라우저 안에서만 처리
- 별도 빌드 없이 GitHub Pages에서 바로 실행 가능

## GitHub Pages 배포 방법
1. 새 GitHub Repository를 만듭니다.
2. 이 폴더 안의 파일들을 Repository 루트에 업로드합니다.
3. GitHub Repository에서 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 `Deploy from a branch`를 선택합니다.
5. Branch를 `main`, Folder를 `/ (root)`로 설정한 뒤 저장합니다.
6. 잠시 후 GitHub Pages 주소에서 사이트를 확인할 수 있습니다.

## 파일 구조
```text
pick-me/
├── index.html
├── README.md
└── .nojekyll
```
