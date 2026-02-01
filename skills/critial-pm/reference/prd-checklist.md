# PRD 완성도 체크리스트

## 1. 문제 정의 (Problem Definition)
- [ ] **해결하려는 문제가 명확한가?**
  - 문제의 근본 원인 (Root Cause) 파악
  - 문제의 정량적 영향도 (Impact) 제시
  - "왜 지금" 이 문제를 해결해야 하는가?

- [ ] **타겟 사용자가 구체적인가?**
  - 페르소나 정의
  - 사용자 규모 및 세그먼트
  - 사용자 Pain Point 검증 방법

- [ ] **현재 상태 (As-Is) 분석이 있는가?**
  - 현재 프로세스/시스템의 한계
  - 기존 해결 시도와 실패 이유
  - Workaround가 있다면 왜 불충분한가?

## 2. 목표 및 성공 지표 (Goals & Success Metrics)
- [ ] **비즈니스 목표가 SMART한가?**
  - Specific: 구체적
  - Measurable: 측정 가능
  - Achievable: 달성 가능
  - Relevant: 회사/팀 목표와 연계
  - Time-bound: 시한 명확

- [ ] **핵심 성공 지표 (KPI)가 정의되었는가?**
  - Primary KPI (반드시 달성)
  - Secondary KPI (부차적 목표)
  - Counter Metric (의도치 않은 부작용 측정)

- [ ] **베이스라인과 타겟이 명확한가?**
  - 현재 수치 (Baseline)
  - 목표 수치 (Target)
  - 목표 달성 시점

## 3. 솔루션 및 범위 (Solution & Scope)
- [ ] **제안된 솔루션이 명확한가?**
  - 핵심 기능/기술 설명
  - Why this approach? (대안 대비 우위)
  - High-level 아키텍처/설계

- [ ] **범위가 명확히 정의되었는가?**
  - In Scope: 이번에 반드시 포함
  - Out of Scope: 명시적으로 제외
  - Future Scope: 향후 고려 사항

- [ ] **MVP가 정의되었는가?**
  - Must-have 기능
  - Nice-to-have 기능
  - Phase 구분 (Phase 1, 2, 3...)

## 4. 요구사항 (Requirements)
- [ ] **기능 요구사항 (Functional Requirements)**
  - User Story 또는 Use Case
  - 각 기능의 우선순위
  - 입력/출력 명세

- [ ] **비기능 요구사항 (Non-functional Requirements)**
  - 성능: 응답시간, 처리량, 동시 사용자
  - 확장성: 성장 대응 방안
  - 보안: 데이터 보호, 인증/인가
  - 가용성: Uptime, 복구 시간
  - 사용성: UX 가이드라인

- [ ] **제약사항 (Constraints)**
  - 기술적 제약 (레거시 시스템, 기술 스택)
  - 비즈니스 제약 (예산, 리소스, 규제)
  - 시간적 제약 (마감일, 의존성)

## 5. 설계 및 사용자 경험 (Design & UX)
- [ ] **사용자 플로우가 정의되었는가?**
  - Happy Path
  - Error/Edge Case 처리
  - 사용자 여정 (User Journey)

- [ ] **UI/UX 가이드라인이 있는가?**
  - 와이어프레임 또는 목업
  - 디자인 시스템 참조
  - 접근성 (Accessibility) 고려

## 6. 기술 및 구현 (Technical Implementation)
- [ ] **기술 스택이 결정되었는가?**
  - 프론트엔드/백엔드 기술
  - 데이터베이스, 인프라
  - 선택 이유 (Trade-off 분석)

- [ ] **데이터 모델이 설계되었는가?**
  - 주요 엔티티 및 관계
  - 데이터 스키마
  - 마이그레이션 전략

- [ ] **API/인터페이스 명세가 있는가?**
  - API 엔드포인트
  - Request/Response 형식
  - 에러 코드 및 처리

- [ ] **외부 의존성이 파악되었는가?**
  - 3rd party API/서비스
  - 내부 시스템 연동
  - 의존성 리스크

## 7. 일정 및 리소스 (Timeline & Resources)
- [ ] **마일스톤이 명확한가?**
  - 주요 단계별 일정
  - Critical Path 식별
  - 버퍼 (Buffer) 고려

- [ ] **리소스 계획이 있는가?**
  - 필요 인력 (개발, 디자인, QA 등)
  - 인프라/도구 비용
  - 외부 협력사 필요 여부

- [ ] **역할과 책임이 명확한가?**
  - DRI (Directly Responsible Individual)
  - Stakeholder 정의
  - 의사결정 프로세스

## 8. 리스크 및 이슈 (Risks & Issues)
- [ ] **주요 리스크가 식별되었는가?**
  - 기술적 리스크
  - 비즈니스 리스크
  - 리소스/일정 리스크

- [ ] **각 리스크에 대한 대응책이 있는가?**
  - 완화 (Mitigation) 계획
  - 우발 상황 (Contingency) 계획
  - 리스크 오너 (Owner)

- [ ] **의존성이 파악되었는가?**
  - Blocker: 진행 불가 요소
  - Dependency: 다른 팀/프로젝트와의 의존
  - 의존성 관리 계획

## 9. 테스트 및 품질 (Testing & Quality)
- [ ] **테스트 전략이 정의되었는가?**
  - 단위/통합/E2E 테스트 범위
  - 성능/부하 테스트 계획
  - UAT (User Acceptance Test) 계획

- [ ] **품질 기준이 명확한가?**
  - Acceptance Criteria
  - Definition of Done
  - Code Review 프로세스

## 10. 배포 및 출시 (Deployment & Launch)
- [ ] **배포 전략이 있는가?**
  - Rollout 계획 (단계적 배포, A/B 테스트 등)
  - Rollback 계획
  - 모니터링 및 알림 설정

- [ ] **커뮤니케이션 계획이 있는가?**
  - 내부 공지 (팀, 회사)
  - 외부 공지 (사용자, 고객)
  - 교육/온보딩 자료

- [ ] **출시 후 계획이 있는가?**
  - 성과 측정 및 리뷰 일정
  - 버그 대응 프로세스
  - Iteration 계획

## 11. 문서 품질 (Documentation Quality)
- [ ] **문서 자체가 명확한가?**
  - 용어 정의 (Glossary)
  - 가정 (Assumptions) 명시
  - 버전 관리 및 변경 이력

- [ ] **이해관계자가 모두 동의했는가?**
  - Review 및 Approval 프로세스
  - Open Question 정리
  - 의사결정 로그

---

## 치명적 누락 패턴 (Critical Red Flags)

### 🚨 즉시 지적해야 할 항목
1. **문제 정의 없이 솔루션부터 시작**
   - "이 기능을 만들자" → "왜? 무슨 문제를 해결하나?"

2. **측정 불가능한 목표**
   - "사용자 경험 개선" → 무엇을, 얼마나, 언제까지?

3. **범위 무한 확장**
   - Out of Scope 없음 → 프로젝트 Scope Creep 위험

4. **리스크 무시**
   - "일정대로 진행하면 됨" → 리스크 대응책 없음

5. **의존성 누락**
   - 다른 팀 작업 필요한데 언급 없음 → Blocker

6. **배포 계획 없음**
   - "개발만 하면 끝" → 출시 후 폭탄

7. **사용자 검증 없음**
   - 내부 가정만 있고 사용자 피드백 없음

### 🎯 우선순위 판단 기준
- **P0 (Critical)**: 없으면 프로젝트 실패
  - 문제 정의, 목표/KPI, MVP 범위, 핵심 리스크

- **P1 (High)**: 없으면 품질/일정 위험
  - 비기능 요구사항, 의존성, 테스트 전략, 배포 계획

- **P2 (Medium)**: 있으면 좋음
  - Future Scope, 상세 설계, 교육 자료