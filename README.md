# HYU AI Writing Quiz

한양대학교 교양 글쓰기 강좌 「AI시대 글쓰기의 힘」(2026-2학기)의 주차별 복습 퀴즈입니다.

Weekly review quizzes for *AI시대 글쓰기의 힘* (The Power of Writing in the AI Era), an undergraduate general-education writing course at Hanyang University (Fall 2026).

## 퀴즈 목록 · Quizzes

| 주차 | 주제 | 문항 수 | 예상 시간 | 바로가기 |
|:---:|---|---|:---:|---|
| 11주차 | 피드백 리터러시와 실질적 수정 | 16문항 (OX 7 · 다지선다 9) | 8분 | [퀴즈 풀기](https://yoohy-hub.github.io/hyu-aiwriting-quiz/week11/) · [소스](week11/index.html) |

### 11주차 · 피드백 리터러시와 실질적 수정

*무엇을 받아들이고 무엇을 거절할 것인가*

출제 범위

- 이론 1: 피드업·피드백·피드포워드 (Hattie & Timperley, 2007)
- 심화: 피드백을 분류하는 단계
- 읽기 자료: 『글이 삶이다』 2부 5 '고쳐쓰기'
- 이론 2: 전역 수정과 국소 수정 (Sommers, 1980)

## 푸는 방법 · How to take a quiz

1. 위 표에서 **퀴즈 풀기**를 누릅니다. PC와 휴대폰 브라우저 모두에서 열리며, 로그인이나 설치는 필요 없습니다.
2. 한 화면에 한 문항씩 나옵니다. 답을 고르면 바로 정답과 해설이 보입니다.
3. 고른 답은 바꿀 수 없습니다. 해설을 읽고 다음 문항으로 넘어갑니다.
4. 마지막 화면에서 점수와 틀린 문항의 해설을 한꺼번에 확인하고, 틀린 문항만 다시 풀 수 있습니다.

Open a quiz link in any desktop or mobile browser; no login is required. Questions appear one per screen with immediate feedback, and the final screen shows your score, explanations for missed items, and an option to retry only those items. Answers are not saved or submitted anywhere.

## 저장소 구조 · Repository structure

```
hyu-aiwriting-quiz/
├── README.md
└── week11/
    └── index.html   # 11주차 퀴즈 (문항·화면·채점이 모두 들어 있는 단일 HTML 파일)
```

- 각 주차 퀴즈는 `weekNN/index.html` 한 파일로 동작하며, 외부 리소스는 Google Fonts(IBM Plex Sans KR, Gowun Batang)만 사용합니다.
- `main` 브랜치에 커밋하면 GitHub Pages로 자동 배포됩니다.
- 새 주차를 추가할 때는 `weekNN/` 폴더에 `index.html`을 넣고, 위 퀴즈 목록 표에 한 줄을 추가합니다.

## 관련 저장소 · Related

- [hyu-writing-quiz](https://github.com/yoohy-hub/hyu-writing-quiz): 같은 학기 외국인 유학생 대상 학부 글쓰기 수업의 주차별 퀴즈

## 만든 사람 · Author

유환일 (Liu Huanyi), 한양대학교 교양국어위원회
