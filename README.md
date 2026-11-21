<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:22d3ee&height=140&section=header&text=Jeong%20Hangyeol&fontColor=ffffff&fontSize=38&fontAlignY=36" alt="Jeong Hangyeol" width="100%" />
</p>

<h3 align="center">
  안녕하세요, 정한결입니다
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="👋" width="28" />
</h3>

<p align="center">
  <b>AI Service · Data · Backend</b><br/>
  떠오른 걸 바로 손으로 만들어 보는 걸 좋아하고, 요즘은 데이터와 AI를 공부하고 있습니다.
</p>

<p align="center">
  <a href="https://github.com/41ways"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://41ways.github.io/norara/"><img src="https://img.shields.io/badge/Games-6366F1?style=flat-square&logo=gamejolt&logoColor=white" alt="Games" /></a>
</p>

---

## 🛠 Tech Stack

**Language**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />

**Framework & Tools**

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" /> <img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" /> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" /> <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" /> <img src="https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="three.js" />

## 🚀 Projects

### 01. 🎧 SWAC — AI 고객과 상담 연습
**AI 실험실 · 프론트엔드** · 2026.11 · 팀 캡스톤  
`Python` `Next.js` `Whisper` `LLM API`

> 상담원이 AI 고객과 통화하며 연습하고, 매뉴얼 항목마다 지켰는지 판정받는 교육 시스템

- **설계** · AI 판정의 인용문을 코드가 원문과 글자 단위로 대조
- **결과** · 묶여 있던 체크를 하나씩 나눠 어김 재현율 **78% → 91%**

[💻 AI·음성 코드](https://github.com/41ways/final-ai-archive)

### 02. 💊 신약 후보물질 독성 예측
**EDA 발표 · 모델링** · 2026.10 · SKALA 미니프로젝트  
`Python` `RDKit` `XGBoost` `LightGBM`

> 라벨 의미가 공개되지 않은 분자 데이터로 독성 여부를 예측

- **분석** · 제약사 3/75 규칙을 데이터에서 재현해 라벨을 심장독성(hERG) 쪽으로 좁힘
- **검증** · 비슷한 분자가 뭉친 데이터라 무작위 교차검증이 점수를 부풀린다는 것을 확인 (AUC 0.875 vs 0.745)

### 03. ⚓ 부산신항 접안 지연 조기경보
**문제 정의 · AIOps · 화면** · 2026.10 · SKALA 조별 과제  
`LSTM` `FastAPI` `MLflow` `Docker`

> 접안 10시간 전에 터미널 예정 시각이 얼마나 틀릴지 예측하는 AIOps 시스템

- **운영** · 배포 게이트, 드리프트 감지, 재학습, 폴백, 미래 정보 누출 테스트
- **결과** · 학습에 쓰지 않은 터미널에서 30분 안 적중 **57% → 87%**

[💻 GitHub](https://github.com/41ways/aiops-team5-berth-early-warning)

### 04. 🛡️ PRISM — 프롬프트 보안 게이트웨이
**처리 흐름 · 출력 검사 · 프론트엔드** · 2026.09 · 팀 미니프로젝트  
`Spring Boot` `Vue 3` `PostgreSQL` `AWS EC2`

> 직원이 생성형 AI에 보내는 프롬프트에서 개인정보·기밀 유출을 막는 게이트웨이

- **설계** · "규칙이 결정하고 AI는 제안만"을 AI 판정 스키마에 결정 필드를 두지 않는 방식으로 강제
- **기여** · 커밋 103개 중 85개

[💻 GitHub](https://github.com/givpro22/secure-prompt-gateway)

### 05. 📝 회의 결정 정리 비서
**개인** · 2026.10  
`LangGraph` `MCP` `Chroma` `Ollama`

> 회의 전사문에서 결정과 할 일을 근거와 함께 뽑고, 과거 결정·사내 정책과 부딪히는지 확인

- **설계** · 모델은 발언 번호만 고르고, 인용과 판정은 코드가 맡음
- **검증** · 처음 보는 회의 40건으로 다시 재서 나온 정확도 47.5%를 그대로 보고하고, 모든 결정을 팀장 승인 초안으로 바꿈

[💻 GitHub](https://github.com/41ways/meeting-decision-ledger)

### 06. 🎫 PlanB Market
**개인** · 2026.08  
`Java 21` `Spring Boot` `JPA` `MyBatis`

> 거래하는 동안에도 가치가 사라지는 티켓·예약권을 사고파는 P2P 거래 백엔드

- **검증** · 20개 스레드 동시 예약 실험에서 중복 예약 5~9건을 비관적 락으로 1건까지
- **설계** · 복식부기 원장으로 돈의 흐름 정합성 확인, 자동 검증 119/119

[💻 GitHub](https://github.com/41ways/planbmarket)

---

## 🎮 쉬는 날 만든 것

| 게임 | 설명 |
| :-- | :-- |
| [의자 쌓기](https://41ways.github.io/chair-stack/) | 의자를 쌓아 올리는 물리 게임, 2D·3D 두 가지에 최대 6명 온라인 |
| [드림 일레븐](https://dream-eleven-board.41ways.workers.dev/) | 카드팩으로 역대 명팀 선수를 모아 챔피언스리그에 도전하는 축구 드래프트 |
| [Next!](https://41ways.github.io/armsdealer/) | 누구에게 무엇을 팔았는지가 결말을 바꾸는 무기 상점 경영 게임 |
| [오디세이](https://github.com/41ways/odyssey) | 오디세우스의 귀향길을 따라가는 3D 액션 로그라이크 |
| [무고](https://github.com/41ways/mugo) | 앞사람의 진술을 판결하고 내 진술을 다음 사람에게 넘기는 탐정 게임 |
| [결투](https://duel.41ways.workers.dev/) | 반응속도 총잡이, 가위바위보 사무라이 |
| [행선지 1~4](https://41ways.github.io/wheretogo/) | 가까운 순서만 보고 오늘의 정답 맞히기 (시·군, 나라, 태양계 천체, 브랜드) |
| [한 줄](https://41ways.github.io/oneline-cal/) | 카드를 한 줄에 놓아 값을 키우는 로그라이크 |
| [우주탐험](https://41ways.github.io/oxy-voyage/) | 심볼 조합으로 산소를 모으는 슬롯머신 로그라이크 |
| [보드게임](https://41ways.github.io/norara/) | 카탄·뱅!·할리갈리 등을 온라인 멀티플레이로 |

[🕹️ 게임 허브에서 전부 보기](https://41ways.github.io/norara/)
