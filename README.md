# 홍준석 (junseok Hong)

**AI.SW 학 · 정보보안 복수전공 | 한신대학교 1학년**

웹 서비스의 취약점 분석과 보안 로그 기반 이상 탐지를 공부하며, 데이터를 안전하게 관리하는 시스템 설계에 관심을 가진 학부생입니다.

[이메일](hong494700@gmail.com) ·  [LinkedIn](https://www.linkedin.com/in/seojin-han-example)

---

## Overview

- 소속: 한신대학교
- 현재 초점: 웹 애플리케이션 취약점 점검 자동화, 서버 로그 기반 이상 행위 탐지
- 학습 중: 클라우드 보안 구성, 데이터 거버넌스, 침해사고 대응 절차
- 관심 문제 영역: 개인정보 보호, 접근 통제, 보안 관제 업무의 효율화
- 협업 및 문의: 보안 스터디, CTF 팀 활동

---

## Research Interests

| 분야 | 세부 관심사 |
|------|-------------|
| Application Security | 웹 취약점 분석(OWASP Top 10), 시큐어 코딩, 정적 분석 도구 활용 |
| Security Analytics | 로그 수집과 정규화, 통계 및 머신러닝 기반 이상 탐지 |
| Information Management | 데이터 분류 체계, 접근 권한 관리, 개인정보 영향 평가 |
| Systems | 리눅스 서버 하드닝, 네트워크 트래픽 분석 |

---

## Technical Skills

| 구분 | 기술 | 수준 |
|------|------|------|
| Languages | Python, C, Java, SQL | Python 주력 / 나머지 활용 가능 |
| Security | Burp Suite, Wireshark, Nmap, Ghidra | 활용 가능 |
| Data & Logs | Pandas, Elasticsearch, Kibana | 활용 가능 |
| Infra | Linux, Docker, Git, GitHub Actions | 활용 가능 |
| Management | ISMS-P 개요, ISO/IEC 27001 개요 | 학습 중 |

---

## Selected Projects

### 웹 서비스 취약점 점검 자동화 도구

- 기간 / 형태: 2026.03 - 2026.06, 팀 3명 (본인: 점검 모듈 및 리포트 설계)
- 문제 정의: 교내 동아리 웹 서비스들이 수동 점검에 의존해 점검 주기가 길고 결과가 일관되지 않음
- 접근 방법: OWASP Top 10 항목 중 인젝션, 인증 결함, 설정 오류를 점검하는 Python 모듈을 구성하고, 결과를 심각도별 리포트로 자동 생성
- 결과: 점검 소요 시간 약 4시간에서 25분으로 단축, 테스트 환경에서 의도적으로 심은 취약점 18개 중 15개 탐지
- 기술: Python, Requests, SQLite, GitHub Actions
- 링크: [Repository](https://github.com/example/web-vuln-scanner)

### 서버 로그 기반 이상 로그인 탐지

- 기간 / 형태: 2025.09 - 2025.12, 수업 프로젝트 (개인)
- 문제 정의: 반복적인 로그인 실패와 비정상 접속 시간대를 사람이 일일이 확인하기 어려움
- 접근 방법: 공개 인증 로그 데이터를 정규화하고, 사용자별 접속 패턴을 기준선으로 삼아 Isolation Forest로 이상 점수 산출
- 결과: 검증 데이터에서 정밀도 0.91, 재현율 0.84, 오탐을 줄이기 위해 임계값 조정 과정을 보고서로 정리
- 기술: Python, Pandas, scikit-learn, Elasticsearch
- 링크: [Repository](https://github.com/example/auth-anomaly) · [Report](https://example.com/report)

### 소규모 조직용 개인정보 처리 현황 관리 시스템

- 기간 / 형태: 2025.03 - 2025.06, 팀 4명 (본인: 데이터 모델 및 접근 권한 설계)
- 문제 정의: 학과 행사 운영 시 수집한 개인정보의 보관 기간과 접근자가 체계적으로 관리되지 않음
- 접근 방법: 개인정보 항목 분류표와 역할 기반 접근 통제(RBAC)를 적용하고, 보관 기간 만료 시 알림을 발송
- 결과: 관리 대상 항목 42개를 5개 등급으로 분류, 만료 데이터 수동 확인 작업 제거
- 기술: Java, Spring Boot, MySQL
- 링크: [Repository](https://github.com/example/privacy-register)

---

## Publications & Reports

- 한서진, "인증 로그 기반 비지도 이상 탐지의 임계값 설정 비교", 한결대학교 정보보안 수업 기말 보고서, 2025.
- 한서진, "OWASP Top 10 실습 환경 구축 및 점검 사례", 개인 블로그 시리즈, 2026.

---

## Experience & Awards

| 기간 | 내용 | 비고 |
|------|------|------|
| 2026.07 - 2026.08 | 보안 관제 업체 하계 인턴십 | 로그 분류 및 탐지 룰 검증 보조 |
| 2025 - 현재 | 교내 보안 동아리 CTF 팀 활동 | 웹 및 포렌식 분야 담당 |
| 2025.11 | 교내 정보보호 경진대회 우수상 | 취약점 분석 보고서 부문 |
| 2026.05 | 정보처리기사 필기 합격 | 한국산업인력공단 |

---

## Education

- 한신대학교 AI.SW 학, 정보보안 (2026 ~)
- 주요 이수 과목: 운영체제, 네트워크, 암호학, 시스템 보안, 데이터베이스, 정보보호 관리, 개인정보 보호법 개론

---

## Contact

- Email: hong494700@gmail.com
