# Buildn

졸업 프로젝트 **Buildn**의 웹 프로토타입. Figma 시안을 1920×1080 기준으로 옮기고, 창 크기에 맞춰 화면 전체를 축소·확대한다.

## 흐름

목표 입력 → 챗봇 질문(스크립트 고정) → Goal Summary → IF moment 선택(3D 카드, 최소 4개) → Final check → 홈 → Scene Record → Archive → Archive 상세

홈 상단 내비의 깃발 아이콘을 누르면 Goal 페이지로 간다. Goal 페이지의 IF-THEN은 온보딩에서 고른 IF로 채워진다.

## 바로가기

주소 뒤에 붙이면 해당 화면부터 열린다.

| 해시 | 화면 |
| --- | --- |
| `#chat-demo` | 챗봇 |
| `#summary` | Goal Summary |
| `#if-moment` | IF moment 선택 |
| `#final-check` | Final check |
| `#buildn-home` | 홈 |
| `#archive` | 아카이브 |
| `#archive-detail` | 아카이브 상세 |
| `#goal` | Goal |
| `#identity` | Identity (근거 그래프 · History 필터) |
| `#create` | Create |
| `#create-chat` | Create 채팅 (LinkedIn Profile) |
| `#create-result` | Create 결과 상세 |
| `#mypage` | My page |

## 구성

- `index.html`: 화면, 스타일, 스크립트를 모두 담은 단일 파일
- `fonts/`: Pretendard Regular·Medium·SemiBold (woff2). Poppins는 Google Fonts에서 불러온다
- `img/`, `video/`: 장면 이미지와 홈 영상
- 빌드 과정 없음. 정적 파일 그대로 GitHub Pages에 올리면 된다

## 폰트 라이선스

Pretendard는 SIL Open Font License 1.1을 따른다.
