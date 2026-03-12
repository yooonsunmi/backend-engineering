# 🚀 Better Code, Stable Service | Backend Developer 윤선미

안녕하세요! 6년의 실무 경험을 바탕으로 **서비스의 안정적인 전환과 고도화**를 고민하는 백엔드 개발자입니다. 
단순히 코드를 짜는 것을 넘어, 레거시 시스템의 현대화와 데이터 정합성 문제를 해결하며 비즈니스 가치를 높이는 데 집중합니다.

---

### 🔥 Technical Challenges & Insights
*보안상 모든 코드를 공개할 수 없으나, 실무에서 해결해온 주요 기술적 도전 과제들을 기록합니다.*

#### 1️⃣ Legacy System Modernization (PHP → Spring Boot)
- **Problem:** 유지보수가 어렵고 장애 추적이 불가능했던 PHP 모놀리식 레거시 환경
- **Action:** Spring Boot 3.x, JPA, Querydsl 기반으로 아키텍처 재설계 및 도메인 중심 리뉴얼 수행
- **Result:** 코드 응집도 향상 및 **긴급 장애 발생 빈도 80% 감소**
> **🔗 관련 기술 포스팅**
> - [PHP 레거시 시스템을 Spring Boot로 전환하며 고민했던 기록들](https://yoonsm45.tistory.com/23)

#### 2️⃣ 데이터 정합성 보장 (Distributed Lock)
- **Problem:** 금융 예치금 결제 및 선착순 로직에서 발생하는 동시성 이슈(Race Condition)
- **Action:** **Redisson(Redis)**을 활용한 분산 락 메커니즘을 도입하여 트랜잭션의 원자성 확보
- **Result:** 데이터 왜곡으로 인한 **수동 보정 업무 0건** 달성 및 시스템 안정화
> **🔗 관련 기술 포스팅**
> - [데이터 정합성을 위한 Redisson 분산 락(Lock) 실무 적용기](https://yoonsm45.tistory.com/18)

#### 3️⃣ 대규모 분산 환경에서의 안정적 서비스 운영
- **Problem:** 서버 다중화 환경에서 스케줄러 중복 실행 및 데이터 경합 문제 발생
- **Action:** Redisson 분산 락을 통해 배치 작업의 유일성을 보장하여 서버 간 정합성 유지
- **Result:** SPOF(단일 장애 지점)를 고려한 설계로 **배치 작업 중복 실행 방지**

#### 4️⃣ 외부 API 연동 및 장애 전파 방지 (Resilience)
- **Problem:** 외부 기관 API 응답 지연/장애가 자사 서비스 전체로 전파되는 리스크
- **Action:** 타임아웃(Timeout) 전략 및 예외 처리 설계를 통해 시스템 결합도(Coupling)를 낮춤
- **Result:** 외부 시스템 불안정 상황에서도 **자사 서비스 가용성 및 연속성 확보**

#### 5️⃣ 효율적인 소통을 지향하는 개발자
- 3년의 퍼블리싱/프론트엔드 경험을 바탕으로 **UI/UX 구조를 깊이 이해하는 API 설계**
- 기획 및 프론트엔드 부서와의 원활한 협업으로 **소통 비용 최소화 및 개발 효율 극대화**

---

### 🛠️ Tech Stack & Tools

#### 🧱 Backend & Core
- **Languages:** Java 11/17, PHP
- **Frameworks:** Spring Boot 3.3.x, JPA (Hibernate), QueryDSL, MyBatis
- **Template Engine:** Thymeleaf

#### 💾 Data & Infrastructure
- **Databases:** MySQL
- **NoSQL & Cache:** Redis (Redisson), ElasticSearch
- **CI/CD:** Jenkins, ArgoCD, GitLab

#### 🎨 Frontend (Full-stack Capability)
- **Web:** HTML5, CSS3, JavaScript, JQuery

#### 🤝 Collaboration & Management
- **Planning:** WBS (Work Breakdown Structure) 기반 일정 관리
- **Management:** Trello, Jira, Confluence, Slack
- **Version Control:** Git (GitLab, Github)

---

### ✍️ Recent Thought & Learning
- [티스토리 블로그 바로가기](https://yoonsm45.tistory.com/)
- 실무에서의 트러블슈팅 사례와 기술적 성찰을 기록하고 있습니다.

---
*“완벽한 기술보다, 상황에 맞는 최선의 해결책을 찾아내는 엔지니어가 되고자 합니다.”*
