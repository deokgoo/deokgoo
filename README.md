# 김덕구 (Deokgoo Kim)

[한국어](#한국어) | [English Version](#english-version)

---

<p align="left">
  <strong>8년차 프론트엔드 개발자</strong><br/>
  스스로를 '프로덕트 엔지니어'로 정의하며, 깊은 오너십을 가진 동료들과 함께 비즈니스 임팩트를 만드는 것을 즐깁니다.<br/>
  CJ올리브영에서 대규모 커머스·콘텐츠 서비스를 개발하고 있으며, 이전에는 일본 후쿠오카 은행에서 금융 웹 서비스를 만들었습니다.<br/>
  레거시 환경에서 새로운 아키텍처로 전환하는 과정에 깊은 관심이 있으며, 코딩하지 않는 날에는 로컬 AI와 3D 프린팅을 다룹니다.
</p>

<p align="left">
  <a href="mailto:kkddgg1001@gmail.com"><img src="https://img.shields.io/badge/Email-kkddgg1001@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/deokgoo"><img src="https://img.shields.io/badge/GitHub-deokgoo-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <a href="https://next-duck-blog.vercel.app"><img src="https://img.shields.io/badge/Blog-Next_Duck_Blog-000000?style=flat-square&logo=next.js&logoColor=white"/></a>
</p>

---

## 한국어

### 소개

2019년 일본 후쿠오카 은행에서 웹 개발을 시작해, 현재는 CJ올리브영에서 커머스와 콘텐츠 영역의 프론트엔드를 개발하고 있습니다.

- **프로덕트 엔지니어 관점**: 단순히 요구사항을 구현하는 데 그치지 않고, 비즈니스 가치와 사용자 경험을 끝까지 책임지는 **프로덕트 엔지니어**로서 일합니다. 강한 오너십을 가지고 주도적으로 몰입하는 동료들과 함께 일하는 것을 지향합니다.
- **아키텍처 전환 경험**: 레거시 아키텍처에서 새롭게 설계되는 모던 아키텍처로 전환하는 프로젝트들을 주로 맡아왔습니다. 기존 환경의 제약을 분석하고, 새로운 기술셋(React, Web Components Lit 등)을 점진적으로 도입해 시스템 안정성과 클라이언트 UX를 개선하는 데 집중합니다.
- **도메인 경험**: CJ올리브영의 대규모 트래픽 환경(커머스, 소셜 SNS, 라이브 스트리밍)과 일본 은행(FFG)의 인증/인가 및 eKYC 시스템을 두루 경험했습니다.
- **Maker & Local Infra**: 코딩 외에도 Mac Studio와 Synology 서버를 기반으로 클라우드 종속 없는 로컬 AI 최적화 파이프라인을 구축해 운영하고 있으며, 3D 프린팅으로 실생활에 필요한 도구를 설계·제작합니다.

---

### 주요 프로젝트 및 경력 (What I've Done)

#### CJ Olive Young (2021.12 ~ 현재)
> H&B 온라인 커머스 및 콘텐츠 서비스 개발

- **리뷰 모던화 전환**
  - 다양한 서비스 아키텍처 위에 리뷰 기능을 일관되게 제공하기 위해 **Web Components (Lit)** 기반의 서빙 및 관리 파이프라인 구현
  - 기존 레거시 환경의 리뷰 대비 부드럽고 자연스러운 클라이언트 UX 제공
- **셔터 (Shutter)**
  - 올리브영의 커머스 SNS 서비스 (스쿼드 리더 참여)
  - 지금까지의 커리어에서 '인생 프로젝트'로 꼽는 서비스로, 이미지 최적화와 HLS 미디어 변환 파이프라인을 구축하며 유저의 업로드부터 클라이언트 로드 및 재생에 이르는 전 과정을 직접 해결, 프론트엔드 개발자로서 가장 큰 성장을 이룬 프로젝트
- **전문관 및 버티컬 서비스 (프리미엄관 · 라이브관 · W Care)**
  - 올리브영의 첫 React 전환 프로젝트를 주도하고 실시간 라이브 방송/VOD 스트리밍 인터페이스를 구현
  - 이미지·영상 Lazy Load, 스켈레톤 UI, 가상화 무한 스크롤을 적용하여 미디어와 대용량 상품 데이터가 집중된 뷰의 렌더링 성능 및 체감 속도 최적화
  - 하이브리드 앱 환경의 W Care 서비스를 위해 네이티브-웹뷰 간 통신을 관장하는 JavaScript Interface(Bridge) 규격을 정립하고 온보딩 회원가입 플로우 설계

#### FFG Fukuoka Bank (2019.04 ~ 2021.11, 일본 현지 근무)
> 일본 후쿠오카 은행 웹 서비스 개발 (2년 8개월)

- **인증/인가 시스템**: OAuth 2.0 기반 그룹 통합 ID 시스템 구축, `oidc-client` 어댑터 구현, 가입 전환율 향상을 위한 UX A/B 테스트
- **eKYC (비대면 본인인증)**: 신분증 OCR 및 얼굴 인식 기반 본인 확인 파이프라인 구축, 개인정보 암호화 처리 및 행원 심사용 관리자 페이지 개발
- **구독/과금 시스템**: 월말 정기 과금 Batch 시스템 및 과금/이벤트 안내 개발
- **관리자 페이지**: 행원 권한 기반 콘텐츠 제어 및 레거시 브라우저(IE 포함) 호환성 대응

#### 이전 경험 & 학력
- **테크워크 (2018 ~ 2019)**: 디지털 앨범 스타트업 창업 및 하이브리드 웹 개발
- **창원대학교 (2013 ~ 2019)**: 정보통신공학과 학사 (자료구조, 알고리즘, OS / Mobile-X 동아리)

---

### 기술 스택 (Stack)

- **Frontend**: Next.js, React, TypeScript, JavaScript, Vue.js, Web Components (Lit), Tailwind CSS, Sass
- **Build & Infra**: Webpack, Vite, Docker, Launchd, Synology NAS, CI/CD
- **Languages**: 
  - 한국어: 모국어
  - 일본어: 비즈니스 및 일상 회화 가능 (일본 현지 2년 8개월 근무)
  - 영어: 기술 문서 독해 및 작성

---

### 그 외 관심사 (What I Do)

#### 로컬 AI & 비용 절감 아키텍처
- **접근 관점**: AI가 실제 비즈니스 서비스에 도입될 때 가장 큰 병목은 지속 불가능한 클라우드 API 호출 비용과 빅테크 종속(Vendor Lock-in 및 가격 인상 리스크)이라고 봅니다. 시중의 상용 API에 무조건 의존하기보다, **직접 튜닝하고 통제할 수 있는 자립적인 인프라**를 갖추는 데 집중하고 있습니다.
- **보유 하드웨어**: **Mac Studio (M5 Max, 36GB 통합 메모리)**, **Synology NAS 서버**
- **활용 툴 및 로컬 모델**:
  - **Hermes Agent**: 자율 코딩 및 워크플로우 자동화 에이전트
  - **MLX 프레임워크**: **Qwen3.8 27B (Dense 코딩 모델)** + **Qwen2.5 7B (컨텍스트 압축·요약 모델)**
  - 36GB 메모리 한계를 극복하기 위해 두 모델을 Metal 메모리 누수 없이 0.5초 만에 교대로 스왑하는 [**`mlx-dynamic-swapper`**](https://github.com/deokgoo/mlx-dynamic-swapper) 프록시를 직접 개발해 100% 로컬 환경으로 운용하고 있습니다.

#### 3D 프린팅
- **자격증 및 장비**: 3D프린터운용기능사 자격증을 보유하고 있으며, **Bambu Lab P1S/P2S**를 메인으로 사용합니다.
- **안전 환경 구축**: 가정 환경에서도 유해가스나 미세먼지 걱정 없이 안전하게 출력할 수 있도록 **챔버 내 음압(Negative Pressure)을 유지하는 외부 공기 배출 덕트 시스템**을 직접 설계·구축했습니다.
- **모델링 및 제작**: **Autodesk Fusion 360**을 사용해 필요한 규격을 직접 설계하며, 어항용 고양이 급식 링 같은 실생활 문제 해결 도구부터 각종 맞춤형 파츠를 제작합니다.

---

<br/>

## English Version

### About Me

Senior Frontend Engineer with 7+ years of experience, building commerce and content services at **CJ Olive Young**, with prior experience developing banking web services at **FFG Fukuoka Bank** in Japan.

- **Product Engineer Mindset**: Beyond implementing UI requirements, I approach challenges as a **Product Engineer** accountable for user experience and business outcomes. I thrive when collaborating with high-ownership colleagues driven to deliver real-world impact.
- **Architecture Migration**: Specialized in transitioning legacy systems into newly architected modern environments. Experienced in identifying existing constraints and incrementally adopting technologies (React, Web Components Lit) to enhance system stability and client UX.
- **Domain Breadth**: Hands-on experience across both large-scale e-commerce traffic (CJ Olive Young: social feeds, live streaming, commerce) and financial web applications (FFG: OAuth 2.0 authentication, eKYC).
- **Maker & Local Infra**: Outside of work, I run a self-hosted, cloudless local AI pipeline powered by Mac Studio and Synology infrastructure, and design functional everyday tools with 3D printers.

---

### Experience (What I've Done)

#### CJ Olive Young (Dec 2021 – Present)
> South Korea’s leading H&B Omnichannel Platform

- **Review Modernization Migration**:
  - Implemented a unified serving and management pipeline using **Web Components (Lit)** to deliver review features consistently across heterogeneous architectures.
  - Delivered a significantly smoother, more natural client UX compared to the legacy review environment.
- **Shutter (Commerce SNS)**:
  - Commerce SNS platform at Olive Young, participated as **Squad Leader**.
  - A definitive career milestone project: spearheaded end-to-end media engineering spanning client-side image optimization, HLS video transcoding pipelines, and seamless upload-to-playback delivery, marking a pivotal period of engineering growth.
- **Specialized Commerce & Vertical Services (Premium Hall, Live Channel, W Care)**:
  - Led Olive Young's initial React migration project and built live streaming / VOD playback interfaces.
  - Applied image/video lazy loading, skeleton UIs, and infinite scroll virtualization to optimize rendering performance across media- and data-intensive views.
  - Standardized the JavaScript Interface (WebView-Native Bridge) communication protocol for the hybrid W Care platform and designed its onboarding sign-up funnel.

#### FFG Fukuoka Bank (Apr 2019 – Nov 2021, Fukuoka, Japan)
> Digital Banking Web Services (2 Years 8 Months on-site)

- **Authentication & Authorization**: Built an OAuth 2.0-based unified ID system using `oidc-client` adapters; ran UX A/B tests to improve sign-up conversions.
- **eKYC Digital Identity Verification**: Developed identity verification workflows integrating ID OCR and facial recognition, with cryptographic safeguards and back-office review portals.
- **Subscription & Billing Systems**: Automated monthly billing batch jobs and billing/event notification pipelines.
- **Admin Management Portal**: Built role-based access control (RBAC) portals with legacy browser (including IE) support.

#### Early Career & Education
- **TechWalk (2018 – 2019)**: Co-founder & Full-Stack Developer at a digital album startup.
- **Changwon National University (2013 – 2019)**: B.S. in Information and Communication Engineering.

---

### Tech Stack

- **Frontend**: Next.js, React, TypeScript, JavaScript, Vue.js, Web Components (Lit), Tailwind CSS, Sass
- **Build & Infra**: Webpack, Vite, Docker, Launchd, Synology NAS, CI/CD
- **Languages**: 
  - Korean: Native
  - Japanese: Conversational / Business (2.8 years on-site engineering in Japan)
  - English: Technical Reading & Writing

---

### What I Do (Beyond Code)

#### Local AI & Cost-Reduction Architecture
- **Perspective**: When AI integrates into real-world production, the fundamental bottlenecks are compounding cloud API bills and vendor lock-in risks. Rather than blindly relying on commercial APIs, I focus on building self-reliant, fine-tunable local infrastructure to hedge against pricing shocks.
- **Hardware Rig**: **Mac Studio (M5 Max, 36GB Unified Memory)**, **Synology NAS Server**
- **Active Stack & Models**:
  - **Hermes Agent**: Autonomous coding and workflow automation.
  - **MLX Framework**: **Qwen3.8 27B (Dense coding model)** + **Qwen2.5 7B (Context compaction/summarization model)**.
  - Designed [`mlx-dynamic-swapper`](https://github.com/deokgoo/mlx-dynamic-swapper), a zero-cost VRAM-swapping proxy that alternates between 27B and 7B models in <0.5s on 36GB unified memory without memory leaks.

#### 3D Printing & Physical Making
- **Certification & Hardware**: Certified Craftsman 3D Printing (3D프린터운용기능사), operating a **Bambu Lab P1S/P2S**.
- **Safety Engineering**: Custom-engineered an active negative pressure air extraction duct system to safely vent VOCs and ultrafine particles in a residential home environment.
- **CAD & Fabrication**: Designing functional parts in **Autodesk Fusion 360**, creating everything from practical home solutions (such as aquarium cat feeding rings) to bespoke hardware enclosures.
