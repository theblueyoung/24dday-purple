---
name: 24dday
description: 잔금일 D-day를 기준으로 이사 할 일·돈·서류를 함께 챙기는 앱
colors:
  violet-primary: "#7A4DFF"
  violet-deep: "#4B2BBF"
  violet-deepest: "#3A1C9C"
  violet-royal: "#5B33E0"
  violet-button-end: "#5D32C7"
  logo-violet: "#6B3FF0"
  metro-dot-violet: "#6A40EC"
  lavender-wash: "#F1ECFF"
  hero-violet-start: "#5425A8"
  hero-violet-mid: "#713BE1"
  hero-violet-end: "#9564EF"
  night-plum: "#2B1252"
  splash-violet-top: "#8E67F2"
  splash-violet-mid: "#6234D0"
  splash-violet-bottom: "#43199C"
  page-violet-glow: "#EDDDFF"
  page-violet-a: "#B697F2"
  page-violet-b: "#D7B8FF"
  page-violet-c: "#D9BAFF"
  mist-lilac-top: "#EEE4FF"
  mist-lilac-mid: "#DCC8FF"
  mist-lilac-end: "#F1DDFF"
  ink-plum: "#29184D"
  ink-plum-soft: "#4F3F6B"
  dusk-gray: "#73658D"
  faded-lilac: "#A497BD"
  plum-chip-ink: "#523579"
  small-button-ink: "#72519C"
  field-icon-ink: "#8C7BB0"
  logo-tile: "#F8F5FF"
  scrim: "rgba(0,0,0,.45)"
  progress-track: "rgba(41,18,94,.4)"
  lilac-tint: "#F1ECFA"
  glass-white: "rgba(255,255,255,.78)"
  blossom-pink: "#FF8FC0"
  blossom-pink-light: "#FF9BC8"
  blossom-pink-deep: "#E4579C"
  bell-off-border: "#FFD6DC"
  mint-done: "#6EE3B1"
  green-done: "#12B886"
  honey-gold: "#FFE17B"
  coral-alert: "#F04452"
  warn-red-ink: "#B4161F"
  kakao-yellow: "#FEE500"
  naver-green: "#03C75A"
typography:
  display:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "56px"
    fontWeight: 800
    lineHeight: 1.05
    letterSpacing: "-2px"
  splash-title:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "40px"
    fontWeight: 800
  amount:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "30px"
    fontWeight: 800
  headline:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "26px"
    fontWeight: 700
    lineHeight: 1.35
  page-title:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "24px"
    fontWeight: 700
  stage-number:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "22px"
    fontWeight: 800
  brand:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "21px"
    fontWeight: 800
  dday-unit:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "20px"
    fontWeight: 600
  title:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "19px"
    fontWeight: 700
  splash-button:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "18px"
    fontWeight: 700
  button:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "17px"
    fontWeight: 700
  body:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "-0.2px"
  list-item:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "15px"
    fontWeight: 600
    lineHeight: "20px"
  label:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "14px"
    fontWeight: 600
  caption:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "12.5px"
    fontWeight: 400
    lineHeight: 1.3
  nav-label:
    fontFamily: "Pretendard, Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic, sans-serif"
    fontSize: "11px"
    fontWeight: 600
rounded:
  check: "5px"
  tag: "8px"
  chip-small: "9px"
  field: "12px"
  button: "16px"
  pill: "18px"
  toast: "14px"
  stage-card: "20px"
  card: "22px"
  feature-card: "24px"
  hero: "27px"
  auth-pill: "27px"
  logo-tile: "29px"
  splash-ring: "30px"
  full: "999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  card-x: "16px"
  card-y: "18px"
  gutter: "20px"
  section: "24px"
components:
  button-primary:
    backgroundColor: "{colors.violet-primary}"
    textColor: "#FFFFFF"
    rounded: "{rounded.button}"
    padding: "16px"
    typography: "{typography.button}"
  button-soft:
    backgroundColor: "#EEE6FF"
    textColor: "{colors.violet-royal}"
    rounded: "{rounded.button}"
    padding: "16px"
  button-white:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.violet-deep}"
    rounded: "{rounded.auth-pill}"
    height: "54px"
  button-danger:
    backgroundColor: "{colors.coral-alert}"
    textColor: "#FFFFFF"
    rounded: "{rounded.button}"
    padding: "16px"
  button-small:
    backgroundColor: "#EEE6FF"
    textColor: "{colors.small-button-ink}"
    rounded: "{rounded.chip-small}"
    padding: "7px 11px"
  card-glass:
    backgroundColor: "{colors.glass-white}"
    rounded: "{rounded.card}"
    padding: "18px 16px"
  hero-card:
    backgroundColor: "{colors.hero-violet-mid}"
    textColor: "#FFFFFF"
    rounded: "{rounded.hero}"
    padding: "20px"
  input-field:
    backgroundColor: "{colors.lilac-tint}"
    textColor: "{colors.ink-plum}"
    rounded: "{rounded.field}"
    padding: "14px"
  stage-tag-current:
    backgroundColor: "{colors.lavender-wash}"
    textColor: "{colors.violet-deep}"
    rounded: "{rounded.tag}"
    padding: "4px 9px"
  stage-tag-done:
    backgroundColor: "#E6F8F1"
    textColor: "{colors.green-done}"
    rounded: "{rounded.tag}"
    padding: "4px 9px"
  bottom-nav:
    backgroundColor: "{colors.night-plum}"
    textColor: "#CDB9F2"
---

# Design System: 24dday

## Overview

**Creative North Star: "든든한 이사 동행"**

24dday는 이사를 준비하는 몇 주 동안 옆에서 "지금 이것만 하면 돼요"라고 알려주는 차분한 동반자예요. 화면은 연한 라일락 안개 위에 흰 유리 카드를 띄우고, 정말 중요한 것(D-day, 지금 단계, 필요한 돈)만 진한 보라 카드로 들어 올려요. 장식보다 정보가 먼저 보이고, 한 화면에서 해야 할 행동은 하나예요.

모바일 한 손 사용이 기본이에요. 앱 폭은 최대 430px이고, 카드 사이 리듬은 일정하게 유지해요. 부품은 단정하고 차분해요. 둥근 모서리와 부드러운 그림자로 친근함을 주되, 색과 움직임은 의미가 있을 때만 써요. 상태는 색 하나만으로 알리지 않고 글자와 아이콘을 함께 써요.

**Key Characteristics:**
- 연라일락 그라데이션 바탕 + 흰 유리 카드로 구역 나누기
- 진한 보라 그라데이션은 히어로·자금 요약·지금 단계에만
- 세 가지 상태 색: 초록(끝냄·보유), 노랑(앞으로 들어옴), 핑크(지금·주의)
- 진한 보라 하단 메뉴, 선택한 탭 위로 볼록 솟은 곡선과 핑크 동그라미
- 쉬운 한국어, 큰 글씨, 넉넉한 누르는 영역

## Colors

보라 한 가족이 화면의 뼈대를 이루고, 초록·노랑·핑크 세 가지 작은 점 색이 상태를 말해요.

### Primary
- **바이올렛** (`violet-primary`): 주 버튼, 체크된 칸, 링크, 선택된 세그먼트. 한 화면의 "다음 행동"을 가리키는 색이에요.
- **딥 바이올렛** (`violet-deep`): 연보라 바탕 위 글씨(지금 단계 꼬리표, 흰 버튼 글씨, 강조 숫자).
- **가장 진한 바이올렛** (`violet-deepest`): 히어로 안의 "지금" 표시.
- **히어로 보라 그라데이션** (`hero-violet-start` → `hero-violet-mid` → `hero-violet-end`, 137°): D-day 히어로, 자금 요약, 서비스 견적 카드.

### Secondary
- **블로섬 핑크** (`blossom-pink`, 메뉴 동그라미는 `blossom-pink` 계열 → `blossom-pink-deep`): 지금 위치와 주의. 하단 메뉴의 선택 동그라미, 히어로의 지금 단계 점, 자금 부족 점.

### Tertiary
- **민트** (`mint-done`): 진한 보라 위의 "끝냄·이미 있음". 진행률 막대, 끝난 단계 점과 선, 보유 금액.
- **허니 골드** (`honey-gold`): 진한 보라 위의 "앞으로 들어올 것". 자금의 받을 돈, 서비스 예상 견적 숫자.
- **그린** (`green-done`): 밝은 바탕 위의 완료 꼬리표 글씨.

### Neutral
- **라일락 안개** (`mist-lilac-top` → `mist-lilac-mid` → `mist-lilac-end`, 160°): 앱 바탕.
- **유리 화이트** (`glass-white`, 12px 블러): 모든 기본 카드.
- **잉크 플럼** (`ink-plum`): 본문 글씨. **잉크 플럼 소프트** (`ink-plum-soft`): 보조 글씨·쉬운 설명. **더스크 그레이** (`dusk-gray`): 날짜·캡션. **빛바랜 라일락** (`faded-lilac`): 비활성 테두리·아이콘에만, 글씨에는 쓰지 않아요.
- **라일락 틴트** (`lilac-tint`): 입력칸·회색 버튼 바탕.
- **야간 플럼** (`night-plum`): 하단 메뉴.
- **코랄** (`coral-alert`)과 **경고 붉은 잉크** (`warn-red-ink`): 로그아웃·삭제 같은 위험한 행동과 실제 오류에만.

- **스플래시 보라** (`splash-violet-top` → `splash-violet-mid` → `splash-violet-bottom`, 160°): 첫 화면과 소개 화면 바탕.
- **페이지 보라** (`page-violet-*`): 컴퓨터에서 앱 바깥 바탕.
- **카카오·네이버 색** (`kakao-yellow`, `naver-green`): 간편 로그인 버튼에만. 브랜드 규정 색이라 바꾸지 않아요.

### Named Rules
**The Three Dots Rule.** 상태 색은 세 가지뿐이에요. 초록 = 끝냄·이미 있음, 노랑 = 앞으로 들어옴, 핑크 = 지금·주의. 홈과 자금, 어느 화면에서든 같은 뜻으로 써요.

**The Quiet Alarm Rule.** 빨강은 되돌릴 수 없는 행동과 실제 오류에만 써요. 지난 일, 부족한 돈 같은 안내는 회색 글씨나 작은 핑크 점으로 조용히 알려요.

## Typography

**Display Font:** Pretendard (with Apple SD Gothic Neo, Noto Sans KR, Malgun Gothic)
**Body Font:** Pretendard (같은 대체 글꼴)

**Character:** 한 가족의 한글 산세리프로 무게만 바꿔 위계를 만들어요. 자간을 살짝 좁혀(-0.2px) 단단하고 또렷하게 읽혀요.

### Hierarchy
- **Display** (800, 56px, 1.05, -2px): 히어로의 D-day 숫자 하나에만.
- **Headline** (700, 26px, 1.35): 로그인·시작 화면의 큰 질문.
- **Page title** (700, 24px): 탭 맨 위 제목(일정, 자금…).
- **Title** (700, 19px): 카드 제목.
- **Button** (700, 17px; 시작 화면 흰 버튼은 18px): 버튼 글씨.
- **Brand / Splash** (800, 21px / 40px): 상단 로고 글씨, 첫 화면 앱 이름.
- **Amount** (800, 30px): 자금 요약의 큰 금액.
- **Body** (400, 16px, 1.5): 입력칸과 일반 문장.
- **List item** (600, 15px, 20px): 할 일·서류 이름.
- **Label** (600, 14px): 입력칸 이름, 날짜, 보조 설명.
- **Caption** (400, 12.5px, 1.3): 목록의 날짜 줄, 작은 안내.
- **Nav label** (600, 11px): 하단 메뉴 글씨.

### Named Rules
**The 14px Floor Rule.** 읽어야 하는 문장은 14px 이상이에요. 12.5px는 날짜·부가 정보 한 줄에만 써요.

## Layout

모바일 한 열 구조예요. 앱은 화면 가운데 최대 430px 폭으로 놓이고, 카드는 양옆 16px, 위로 14px 간격으로 쌓여요. 카드 안 여백은 위아래 18px, 양옆 16px이에요. 페이지 머리(제목+설명)는 양옆 20px이에요. 목록 한 줄은 위아래 12px이고, 줄 사이는 얇은 라일락 선으로 나눠요. 하단 메뉴는 화면 아래 고정이고, 내용 아래에 52px를 비워 가려지지 않게 해요. 시작·로그인·이사 정보 화면은 메뉴 없이 세로 가운데 정렬이에요.

## Elevation & Depth

격층형이에요. 바탕(라일락 안개) → 유리 카드(연한 그림자) → 진한 보라 카드(깊은 그림자) 세 층으로 중요도를 나타내요. 그림자는 모두 보라 기운이 도는 색이고, 검정 그림자는 쓰지 않아요.

### Shadow Vocabulary
- **유리 카드** (`box-shadow: 0 7px 20px rgba(75,42,119,.07)`): 모든 기본 카드.
- **지금 단계 카드** (`box-shadow: 0 10px 24px rgba(99,64,189,.16)` + 보라 테두리 1.5px): 일정의 현재 단계 묶음.
- **히어로·자금 요약** (`box-shadow: 0 14px 28px rgba(87,48,149,.28)`): 진한 보라 카드.
- **주 버튼** (`box-shadow: 0 8px 18px -10px rgba(93,50,199,.7)`): 보라 버튼 아래 은은한 빛.

### Named Rules
**The Three Layers Rule.** 한 화면에서 진한 보라 카드는 맨 위 하나(히어로 또는 요약)뿐이에요. 나머지는 유리 카드로 둬야 시선이 흩어지지 않아요.

## Shapes

모든 모서리가 둥글고, 크기가 클수록 더 둥글어요. 체크칸 5px, 꼬리표 8px, 작은 버튼 9px, 입력칸 12px, 버튼 16px, 칩 18px, 카드 22px, 진한 카드 24px, 히어로와 흰 버튼 27px. 아바타와 하단 메뉴 동그라미는 완전한 원이에요. 하단 메뉴 위의 볼록한 곡선(150×24px)이 이 앱의 대표 모양이에요.

## Components

### Buttons
단정하고 차분해요. 화면당 주 버튼은 하나예요.
- **Shape:** 부드럽게 둥근 모서리(16px), 화면 폭 가득.
- **Primary:** 바이올렛 그라데이션(135°, `violet-primary` → `violet-button-end`), 흰 글씨 17px 700, 안쪽 여백 16px, 보라 빛 그림자.
- **Soft:** 연보라 바탕(`#EEE6FF`) + 진한 보라 글씨. 보조 행동(취소가 아닌 두 번째 선택).
- **White:** 흰 바탕 + 딥 바이올렛 글씨, 54px 높이 알약 모양(27px). 시작·로그인 화면 전용.
- **Danger:** 코랄 바탕 흰 글씨. 로그아웃·삭제 확인에만.
- **Small (수정 등):** 연보라 바탕, 13px 600, 9px 모서리. 목록 줄 오른쪽.
- **Focus:** 2px 바이올렛 윤곽선, 2px 띄움.

### Chips
- **Style:** 반투명 흰 바탕 + 흰 테두리, 18px 모서리, 14px 600.
- **State:** 선택되면 바이올렛 바탕 흰 글씨.

### Cards / Containers
- **Corner Style:** 22px.
- **Background:** 유리 화이트, 12px 배경 블러, 1px 흰 테두리.
- **Shadow Strategy:** Elevation의 유리 카드.
- **Internal Padding:** 18px 16px.

### Inputs / Fields
- **Style:** 라일락 틴트 바탕, 테두리 없음, 12px 모서리, 14px 여백, 16px 글씨(아이폰 확대 방지).
- **Auth 화면:** 52px 높이, 20px 모서리, 흰→연보라 그라데이션, 왼쪽에 아이콘 상자.
- **Focus:** 2px 바이올렛 윤곽선.

### Navigation
- **Style:** 야간 플럼 띠, 5개 탭(아이콘 24px + 11px 글씨), 비선택 `#CDB9F2`, 선택 흰 글씨 700.
- **Active:** 선택한 탭 위로 띠가 볼록 솟고(150×24px), 핑크 동그라미(50px)가 그 안에서 아이콘을 받쳐요. 탭을 바꾸면 곡선과 동그라미가 0.35초 동안 미끄러지듯 이동해요. 움직임 줄이기 설정에서는 바로 바뀌어요.

### Stage Tag (signature)
단계 꼬리표는 "N단계: 이름 (상태)" 글자로 상태를 말해요. 지금 단계는 연보라 바탕 + 딥 바이올렛, 완료는 연초록 바탕 + 그린 + 체크 아이콘, 앞으로 올 단계는 옅은 라일락 바탕 + 소프트 잉크.

### Hero D-day Card (signature)
히어로 보라 그라데이션 위에 잔금일, 56px D-day 숫자, 민트 진행률 막대, 4개 단계 점(끝냄 민트, 지금 핑크, 앞으로 보라)을 담아요. 지금 단계 점은 천천히 두근거려요(움직임 줄이기 시 멈춤).

### Bottom Sheet
아래에서 올라오는 흰 창, 위쪽 모서리 24px, 최대 높이 90%, 오른쪽 위에 연보라 원형 닫기 버튼(40px). 수정·확인·추가는 모두 이 창에서 해요.

## Do's and Don'ts

### Do:
- **Do** 상태는 The Three Dots Rule의 세 색과 함께 글자로도 적어요("완료", "날짜 지남", "부족").
- **Do** 진한 보라 카드는 화면 맨 위 하나만 써요.
- **Do** 누르는 영역은 44px 이상으로, 작은 체크칸은 보이지 않는 여백으로 넓혀요.
- **Do** 어려운 용어의 쉬운 설명은 필요할 때 펼쳐 보게 해요(? 버튼, 수정 창).
- **Do** 움직임은 `prefers-reduced-motion`에서 멈춰요.

### Don't:
- **Don't** 안내 문구에 진한 빨강 굵은 글씨를 쓰지 마세요(The Quiet Alarm Rule).
- **Don't** 지금 단계 꼬리표를 진한 핑크로 칠하지 마세요. 연보라 바탕 + 딥 바이올렛이에요.
- **Don't** 빛바랜 라일락(`faded-lilac`)을 읽어야 하는 글씨에 쓰지 마세요.
- **Don't** 쉬운 설명을 목록에 늘 펼쳐 두지 마세요. 글이 많아지면 시선이 흩어져요.
- **Don't** 버튼에 진한 핑크 바탕을 쓰지 마세요. 시작 화면 버튼은 흰 바탕 + 보라 글씨예요.
