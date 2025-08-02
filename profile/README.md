# ☕ SigorTalk

믿을 수 있는 농부를 찾고 그 농부를 응원하는 소비자를 연결합니다.

## 🔗 Repositories

| 📁 Repository                          | 설명                                |
|-----------------------------------------|---------------------------------------|
| [coffee-bara-frontend](https://github.com/koffeebara/Frontend-React) | 프론트엔드 (React.js + TypeScript)    |
| [coffee-bara-backend](https://github.com/koffeebara/Backend-Spring-Boot)   | 백엔드 (Spring Boot + MySQL)         |
| [coffee-bara-infra](https://github.com/koffeebara/sigortalk-infra)       | Terraform, Ansible 인프라 구성 코드 |
| [coffee-bara-docs](https://www.notion.so/228c94c8d6d180f6b31dd5af4191e91a)         | 기획 및 산출물 문서                  |

좋습니다! 아래는 ‘시고르팜(SigorFarm)’ – 농작물 펀딩형 서비스에 맞게 리드미를 전면 수정한 버전입니다. 귀촌 청년과 로컬 농부를 연결하고, 소비자 참여형 펀딩 구조로 전환된 내용을 반영했습니다.

---

🌾 시고르팜 (SigorFarm)

“도시에서 응원하고, 시골에서 자라나는 농작물 이야기”
로컬 농부의 진심을 담은 유기농 펀딩 플랫폼

---

📋 프로젝트 개요

🎯 Target Audience
	•	🧑‍🌾 작은 규모로 농사를 짓는 로컬 생산자
	•	🧑‍💻 유기농 식재료나 생산자의 스토리에 관심 있는 도시 소비자
	•	🏛 지역 내 농촌 활성화와 직거래 기반 유통 확대를 원하는 지자체

---
💡 Pain Points
	•	농부: 판매 경로 부족, 브랜딩 어려움, 초기 자금 확보의 부담
	•	소비자: 농작물에 대한 정보 부족, 무작위적 유통 구조에 대한 불신
	•	지자체: 고령화된 농촌과 청년 귀촌 정책 간의 연결 고리 부족

---

🌱 Solution – 시고르팜이 제안하는 방식
	1.	누구나 참여 가능한 농작물 펀딩 오픈
농부가 직접 작물의 이야기, 재배 과정, 목표를 제시하고 소비자는 후원 형태로 참여
	2.	AI 기반 병해충 이미지 진단 & 작물 관리 지원
농작물 사진 기반으로 병해충 여부를 AI가 분석, 농부에게 빠른 대응 가이드 제공
	3.	스토리텔링 중심 콘텐츠 & 직거래 유통 구조
수확 전 일지 기록과 사진 공유로 소비자와 정서적 연결, 신뢰 기반 직거래 구조 형성

---

⚙ 주요 기능

👨‍🌾 농부
	•	로그인 후 농작물 펀딩 개설 (사진, 스토리, 생산 목표 등 입력)
	•	병해충 진단 AI 기능 사용 (사진 업로드 기반)
	•	후원자와의 일지 기반 커뮤니케이션 기능

👨‍👩‍👧 소비자
	•	펀딩 리스트 탐색 및 생산자 스토리 기반 참여 결정
	•	농작물 성장 일지를 확인하고 생산자와 교류
	•	수확 후 직배송 또는 지역 픽업 기반 수령

🏛 지자체
	•	농촌 콘텐츠를 축적하고 귀촌 정책에 연계
	•	지역화폐 또는 제도적 지원과 플랫폼 연동
	•	로컬 브랜딩 및 공공 직거래 마켓 연계 가능

---

🗓 마일스톤
	•	✅ Week 1: 펀딩 생성 기능 및 생산자 등록 구조 설계
	•	✅ Week 2: 이미지 기반 병해충 분석 AI API 연동
	•	✅ Week 3: 펀딩 참여/후원 기능 구현, 결제 모듈 설계
	•	✅ Week 4: 일지 작성 기능 및 소비자 알림 시스템 구현
	•	✅ Week 5: 전체 통합 및 시연용 MVP 완성

---

🚀 Tech Stack

🌐 Frontend
	•	React.js
	•	TypeScript

🛠 Backend
	•	Java 21
	•	Spring Boot 3
	•	JPA / Hibernate
	•	Spring Security
	•	REST API, JWT 인증

🗄 Database
	•	MySQL

🧠 AI 연동
	•	OpenCV or 외부 AI API (병해충 진단)
	•	클라우드 기반 스토리지 (사진 업로드/공유)

📦 Infra
	•	Docker
	•	Terraform, Ansible
	•	Prometheus + Grafana (모니터링), Dozzle (로깅)

---

🛠 Tools
	•	Figma (UX/UI 디자인)
	•	Git, GitHub Actions (CI/CD)
	•	Notion, Discord (팀 협업)

---

👥 Team Collaboration

시고르팜은 기술과 로컬 삶이 만나는 지점을 고민하는 개발자, 디자이너, 기획자가 함께
농부의 진심을 소비자에게 전달하는 새로운 농업 펀딩 문화를 만들어가고 있습니다.

⸻

✅ 한 줄 슬로건

“당신의 후원이, 시골 한켠에서 싹을 틔웁니다 – SigorFarm”



