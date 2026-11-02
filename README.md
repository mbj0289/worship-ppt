# 찬양 가사 PPT 제작 웹앱

## GitHub Pages 배포
1. 이 폴더 안의 파일 전체를 GitHub 저장소 루트에 업로드합니다.
2. 저장소에서 Settings → Pages를 엽니다.
3. Build and deployment에서 Deploy from a branch를 선택합니다.
4. Branch는 main, 폴더는 /(root)로 선택하고 Save를 누릅니다.
5. 배포가 완료되면 제공된 GitHub Pages 주소를 iPhone Safari에서 엽니다.
6. iPhone 공유 버튼 → 홈 화면에 추가를 누릅니다.

## 기능
- 제목/가수 검색 시 네이버 VIBE 검색 창 열기
- 가사 붙여넣기, 자동 슬라이드 분할
- 미리보기, 수정, 복제, 삭제, 순서 변경
- 배경/글꼴/글자 크기/색상 설정 및 PPTX 다운로드
- 웹앱 아이콘, manifest, service worker 포함

## 글꼴 목록
Chrome의 Local Font Access API가 지원되는 환경에서 버튼을 누르고 권한을 허용하면 설치된 글꼴을 읽어 목록에 표시합니다. iPhone Safari에서는 기기의 전체 글꼴 목록을 읽는 기능이 제한될 수 있습니다.


## 최신 기능
- 세련된 글꼴 선택: Pretendard, SUIT, Noto Sans KR, Montserrat, 고운 바탕 등
- 이미지 파일을 업로드해 모든 슬라이드의 배경 이미지로 사용
- 곡 제목만 우측 상단에 표시되는 빈 슬라이드 추가
- 가사 자동 생성 시 슬라이드당 최대 두 줄로 분할
