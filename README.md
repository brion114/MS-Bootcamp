# 🌐 MS-Bootcamp 네트워크 & 보안 실습 포트폴리오

경기인력개발원 부트캠프 과정 중 진행한 네트워크 라우팅, NAT, 서버 서비스 구축 및 보안 관제 실습 기록입니다.

---

## 🛠️ 주요 학습 및 실습 내용

### 1. 동적 라우팅 프로토콜 (OSPF & RIPv2)
- 정적 라우팅(Static) 대비 동적 라우팅의 경로 자동 수렴 과정 실습
- 관리 거리(AD) 및 OSPF Cost(대역폭 기반 메트릭) 계산 원리 이해
- 링크 장애 발생 시 LSA를 통한 빠른 수렴(Convergence) 동작 검증

### 2. NAT 4종 (Normal, Reverse, Redirect, Exclude)
- **Normal NAT (PAT)**: 사설 IP 대역의 공인 IP 변환 및 인터넷 통신 구성
- **Reverse NAT / Port Forwarding**: DMZ 내부 웹서버(80) 외부 공개
- **Exclude NAT**: ACL `deny` 구문을 활용하여 파트너망 통신 시 원본 사설 IP 보존

### 3. 서버 서비스 & 보안 관제 (SOC / SIEM 원형)
- **DHCP / DNS / HTTP**: DORA 과정을 통한 자동 IP 할당 및 도메인 이름 해석 웹 접속 구축
- **NTP & Syslog**: 로그 신뢰성 확보를 위한 시간 동기화 및 중앙 로그 수집 환경 구축
- **Port Security 연동**: 포트 위반 발생 시 Syslog 서버로 실시간 이벤트 로그 수집 확인

---

## 📁 주요 실습 파일
- `12 동적 라우팅 설정OSPF.docx` / `정적라우팅완성(OSPF).pkt`
- `NAT_실습_v1.docx` / `Nat-PAT to PC1.pkt`
- `영역3_서버서비스_완전실습(part3).docx` / `1.pkt`
