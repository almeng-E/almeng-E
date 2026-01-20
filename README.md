# 안녕하세요, 기술의 'Why'를 탐구하여 구현하는 풀스택 개발자 최원민입니다. 👋

> **"You've got to start with the customer experience and work backwards to the technology."**
> <br>- Steve Jobs

저는 단순히 명세서대로 기능을 구현하는 것을 넘어, **사용자의 경험(Why)에서 시작해 최적의 기술(How)을 설계**하는 Full Stack 개발자입니다.

인문학적 분석력과 클라이밍 강사로서의 소통 경험을 바탕으로, **비개발자의 모호한 요구사항을 명확한 기술 언어로 번역**하고 **데이터 기반의 의사결정**을 하는 훈련을 해 왔습니다.
이후 삼성청년SW·AI아카데미를 우수 수료하며, 그 과정에서 **알고리즘 역량**과 **구현 역량**을 함양하여 여러 프로젝트들을 성공적으로 이끌었습니다.

---

## 🚀 **핵심 역량**

- **성능 최적화 역량**: 웹 캔버스 렌더링 성능 최적화 (780ms → 12ms) 및 공간 분할 알고리즘 도입 경험.
- **유저 중심 기획 역량**: 400여 명의 실무자 VoC를 기반으로 업무 프로세스를 디지털 스레드(Digital Thread)로 구축.
- **소통과 리더십**: 2년간의 강사 경험과 13회(학부 10회/ SSAFY 3회) 프로젝트 팀장 경험을 통해 조직의 이해관계를 조율한 경험.
- **알고리즘 역량**: 백준 Platinum 1 (상위1%) 역량 및 300일동안 매일 문제풀이 중.
- **AI 적용 역량**: LLM/LMM을 활용한 RAG 파이프라인 구축 및 서비스 기능 고도화.

---

## 🛠️ **Tech Stack**

| Category | Skills |
| --- | --- |
| **Frontend** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white) `Konva.js` |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) |
| **AI & Data** | `LangChain` `RAG Pipeline` `Prompt Engineering` (CoT, Few-shot) |
| **DevOps & Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |

---

## 🏆 **프로젝트 경험**

<details>
<summary>1. 삼성전자 네트워크사업부 | 웹 기반 PCB CAD 협업 플랫폼 <b>(팀장 / FE Architect)</b></summary>

<br>

> **👥 팀 구성** : 6인 (삼성전자 네트워크사업부) <br>
> **👑 주요 역할** : **팀장**, 프론트엔드 (Canvas Drawing Module), 기획 <br>
> **🛠 기술 스택** : ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)  `Konva.js` `OOP`

<br>

**S (Situation): 데이터 파편화로 인한 비효율 발생**
* 삼성전자 네트워크사업부 내 400여 명의 연구원들이 PCB 설계를 위해 엑셀(Excel), Visio 등 서로 다른 툴을 사용하고 있었습니다.
* 이로 인해 데이터 취합 및 변환 과정에서 병목 현상이 발생했고, 디지털 트윈(Digital Twin) 구축을 위한 데이터의 연속성(Digital Thread)이 끊겨 있는 상태였습니다.

**T (Task): 설계 프로세스 자동화 및 대용량 웹 캔버스 구현**
* 수작업 위주의 설계 프로세스를 웹 기반으로 자동화하여 업무 효율을 극대화하고, 설계 데이터를 DB화하는 목표를 수립했습니다.
* 2,000개 이상의 부품 객체를 웹 브라우저 상에서 끊김 없이 렌더링하고 조작해야 하는 고성능 프론트엔드 과제가 주어졌습니다.

**A (Action): VoC 기반 기획과 공간 분할 알고리즘을 통한 최적화**
* **[기획/소통] VoC 기반 애자일 개발**: 현업 실무 담당자 10여 명을 인터뷰하여 명세서 너머의 숨겨진 니즈를 파악하고, 매 주 2개 팀이상의 회의에 참석하여 각 팀의 모호한 요구사항을 **Business Impact**를 기준으로 구체화하여 6주간의 개발 사이클을 주도했습니다.
* **[기술/성능] Uniform Grid 공간 분할**: 2,000개 부품 렌더링 시 발생하는 딜레이(780ms)를 해결하기 위해 게임 개발에서 쓰이는 공간 분할 기법(Uniform Grid)을 도입했습니다. Point query와 range query의 탐색 시간 복잡도를 $O(N)$에서 Amortized $O(1)$로 낮춰 렌더링 성능을 **12ms**로 98% 단축했습니다.
* **[아키텍처] VanillaJS & OOP**: 프레임워크 의존성을 제거하고 유지보수성을 높이기 위해 VanillaJS를 채택했습니다. CAD 서비스의 클라이언트 상태 관리는 Pub-Sub 패턴의 커스텀 이벤트 아키텍처를 직접 설계하고 적용하여 확장 가능한 코드를 작성했습니다.

**R (Result): 연간 1600시간 절감 성과 달성**
* 기존 7일이 소요되던 설계 검증 프로세스를 **3일로 단축(50% 이상 효율화)**했습니다.
* 특히 열해석 시뮬레이션을 위한 데이터 입력 시간을 **7일에서 1시간 이내로 99% 단축**하여, 연간 약 1,600시간의 공수를 절감하는 성과를 냈습니다.

> **6주간 MVP 개발하는 일정이었으나, 성과를 인정받아 프로젝트 기간이 6주 연장되어 400여명 실무진의 VoC를 기반으로 메이저 업데이트를 진행했습니다.**

</details>

<details>
<summary>2. PicTale: AI 인터랙티브 그림책 플랫폼 <b>(팀장 / FE / 기획)</b></summary>

<br>

> **👥 팀 구성** : 6인 <br>
> **👑 주요 역할** : **팀장**, 프론트엔드 (UX/Interactive), 기획 <br>
> **🛠 기술 스택** : ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) `Langchain`

<br>

#### 🎨 Role 1: Frontend Developer (UX/UI & Interactive)

**S (Situation): 유아 사용자를 위한 인터페이스 부재**
* 기존 AI 생성 서비스들은 텍스트 프롬프트 입력이 필수적이어서, 글을 모르는 3~6세 유아들이 주도적으로 사용하기 어렵다는 진입 장벽이 있었습니다.

**T (Task): 'Typing-Free' UX 설계 및 구현**
* 텍스트 입력 없이 아이들이 직관적으로 이야기를 만들 수 있는 **Non-typing 인터페이스**를 구축해야 했습니다.

**A (Action): Atomic Design 도입 및 직관적 인터랙션 구현**
* **UX 설계**: Figma를 활용해 아이들이 그림을 그리거나 블록을 조립하는 방식의 UX를 설계하여 텍스트 의존도를 제거했습니다.
* **컴포넌트 시스템**: 기존 UI 컴포넌트를 활용하기보다, 논문을 2편 분석하여 직접 UI를 기획하였습니다. 버튼 및 UI 요소를 **Atomic Design** 패턴으로 모듈화하여 재사용성을 높이고 디자인 일관성을 확보했습니다.
* **Vibe Coding**: React와 TypeScript 환경에서 GitHub Copilot과 MCP를 적극 활용하는 '바이브 코딩'을 통해 개발 생산성을 극대화했습니다. 남은 공수는 프로젝트 안정화에 투자하였습니다.

**R (Result): 타겟 사용자 맞춤형 서비스 완성**
* 유아 친화적인 UI/UX로 서비스 접근성을 획기적으로 개선했습니다.
* 기존 다른 서비스(Gemini Storybook)와 다른 AI 스토리북 서비스를 구현하였습니다.

#### ⚙️ Role 2: Backend & AI Engineer (Architecture & Pipeline)

**S (Situation): 생성형 AI의 일관성 부족 및 지연 시간**
* 사용자가 그린 낙서(Drawing)를 AI가 인식하여 동화 삽화로 변환해야 했으나, 단순 프롬프트만으로는 그림체의 일관성을 유지하기 어려웠고 생성 시간이 오래 걸리는 문제가 있었습니다.

**T (Task): 고품질 이미지 생성 파이프라인 및 응답 속도 최적화**
* 사용자 그림의 특징을 반영하면서도 고품질의 동화 스타일을 유지하는 파이프라인을 구축하고, 대기 시간을 최소화해야 했습니다.

**A (Action): LMM 파이프라인 구축 및 비동기 처리**
* **AI 파이프라인 설계**: 토큰 절약과 레이턴시 감소를 위해 유저의 그림에서 메타데이터(특징)를 추출하고, 이를 LLM(GPT-4o)이 최적화된 프롬프트로 변환한 뒤 이미지 모델(Imagen-3)에 전달하는 **RAG 기반 LMM 파이프라인**을 구축했습니다.
* **성능 최적화**: 텍스트 생성과 이미지 생성을 병렬로 처리하는 비동기 아키텍처를 도입하여 전체 응답 속도를 **약 75% 단축**했습니다.

**R (Result): 몰입감을 해치지 않는 실시간성 확보**
* text-to-image로 적은 image-to-image에 비해 토큰을 사용하며 삽화 이미지의 연속성을 보장할 수 있었습니다.
* 10p 기준 동일 분량의 Gemini Storybook에 비해 4배 빠른 속도로, 사용자의 의도가 정확히 반영된 고품질 동화책 생성 시스템을 완성했습니다.

</details>

<details>
<summary>MiniPJT</summary>

<br>

- **AI RAG project** (**팀장** / RAG 설계·평가 / BE)  
  `2025.06` `Langchain` `RAG` `Fast API` `Git`

- **도서 커뮤니티 & 독후감 작성 도우미 챗봇** (**팀장** / FE + BE / Git 관리 / 챗봇 설계·평가)  
  `2025.05` `Django DRF` `REST API` `ChatBot` `Vue.js` `Git`

- **캡스톤디자인: 유튜브 대본 기반 채널 분석 서비스 (대학교 채널)** (데이터 수집 with Langchain)  
  `2024.11 ~ 2024.12` `Langchain`

</details>

---

## 🎓 **Education**

* **OPIc AL** (2025.05)
* **삼성청년SW·AI아카데미(SSAFY) 13기** | *13기 우수 수료 (2025.01 ~ 2025.12)*
* **명지대학교** | *아랍지역학과 & 인문ICT콘텐츠 융합전공 (2019.03 ~ 2025.02)*
    * 인문학적 소양과 IT 기술을 융합하여 데이터 분석 및 서비스 기획 역량 함양.

---

## 🧩 **추가 역량**

### 📐 Algorithm Solving
* **Baekjoon Platinum 1** (상위 1%)
* 삼성SW역량평가 A+ (모의)
* **DP 스터디 주최 경험**:
    * 스터디장으로서 학습 자료 제작 및 핵심 문제 큐레이션 진행.
    * 참여도 저조 문제를 해결하기 위해 '공유 문화'를 정착시켜 참여율 30% → 80% 달성.
    
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=cj98123)](https://solved.ac/cj98123/)

### 🧗‍♂️ 커뮤니케이션 역량 (강사 경험)
* **상대방의 언어로 소통**: 클라이밍 강사 시절, 수의학 전공 수강생에게 '삼지점'을 '무게중심과 벡터'의 원리로 설명하여 성과를 낸 경험이 있습니다.
	* 이 경험은 현재 개발자로서 **비개발 직군(기획, 디자인, 현업 연구원)과의 소통**에서 상대방의 언어로 기술을 번역하여 전달하는 핵심 역량이 되었습니다.

---

