# modoIT Blog Profit Engine

블로그 주제 발굴부터 SEO 원고 작성, 이미지 기획·생성, 수익화, 콘텐츠 재활용, 블로그 임시 저장 검증까지 지원하는 Codex 스킬입니다.

## 주요 기능

- 수익성 있는 블로그 주제 3개 비교 및 초보자용 1순위 추천
- 독자와 검색 의도 분석, 키워드 3~4개 및 대장 키워드 선정
- 대장 키워드가 포함된 제목 후보 3개와 블로그 원고 작성
- 선정 키워드별 본문 3~4회 사용 여부 검증
- 자연스러운 한국어 편집과 허위 경험·후기·수치 생성 방지
- 시험 모드 이미지 3장, 운영 모드 이미지 15장 기획·생성
- 해시태그와 검색 유입 사전 점검
- 블로그 편집기 임시 저장 후 저장본 재검증
- 광고·제휴·상품 수익화와 6~12개월 성장 로드맵

## 설치

Codex 대화창에 아래 문장을 그대로 입력하세요.

```text
$skill-installer를 사용해서 https://github.com/anais030505-cmyk/modoit-blog-profit-engine/tree/main/skills/blog-profit-engine 의 스킬을 설치해줘.
```

설치 후 스킬이 보이지 않으면 Codex를 다시 시작하세요.

### 수동 설치

이 저장소를 내려받아 `skills/blog-profit-engine` 폴더를 아래 위치에 복사합니다.

- macOS/Linux: `~/.codex/skills/blog-profit-engine`
- Windows: `%USERPROFILE%\.codex\skills\blog-profit-engine`

## 빠른 시작

### 시험 모드

```text
$blog-profit-engine를 사용해 네이버 블로그 글을 작성해줘.

시험 모드로 진행하고 이미지는 3장 만들어줘.
키워드 규칙과 검색 유입 점검을 완료한 뒤 블로그 편집기에 임시 저장해줘.
저장한 글을 다시 열어 제목, 본문, 이미지, 해시태그를 검증해줘.
공개 또는 예약 발행은 절대 하지 마.
```

### 운영 모드

```text
$blog-profit-engine를 운영 모드로 실행해줘.
이미지는 15장 기획하고 생성해줘.
최종 결과는 임시 저장까지만 진행하고 공개 발행하지 마.
```

## 사용 전 확인

- 블로그 로그인은 사용자가 직접 완료해야 합니다.
- 계정 비밀번호, 인증번호, 쿠키를 다른 사람에게 공유하지 마세요.
- 이미지 생성과 브라우저 제어 가능 여부는 사용 환경에 따라 다릅니다.
- 이 스킬은 공개·예약 발행을 수행하지 않고 임시 저장까지만 진행합니다.
- 작성된 글의 사실관계, 직접 경험, 광고·제휴 고지는 사용자가 최종 확인해야 합니다.

## 스킬 구성

```text
skills/blog-profit-engine/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── monetization.md
    ├── publishing-workflow.md
    ├── research-seo-growth.md
    └── writing-recycling.md
```

## 버전

- `v1.0.0`: 최초 공개 버전
