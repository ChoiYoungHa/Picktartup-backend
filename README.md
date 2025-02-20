# 💰 블록체인 기반 스타트업 조각 투자 플랫폼 Picktartup
![Image](https://github.com/user-attachments/assets/0c776128-896b-4e02-a3e8-230239b77c2f)



# 👀 Intro

### 도메인 소개
### ⛓️ 블록체인이란?

블록체인은 네트워크 참여자 전원이 거래 내역 등을 공유·저장할 수 있는 **분산 데이터 처리 기술**입니다.  
주요 특징은 **블록(block)** 안에 거래 정보가 기록되고, 이러한 블록들이 서로 연결되어 **체인(chain)** 형태를 이루며 이를 통해 **공공 분산 원장(public distributed ledger)** 역할을 수행한다는 점입니다.

- **분산 저장**: 네트워크에 참여하는 모든 노드가 동일한 거래 데이터를 복사해 가지고 있습니다.  
- **블록 구조**: 거래 내역이 기록된 블록들이 연결되어 체인 형태를 형성합니다.  
- **P2P 방식**: 중앙 서버 없이, 참여 노드 간 직접 거래(거래장부 대조 및 검증)가 이뤄집니다.

---

### 🔐 신뢰성을 보장할 수 있는 근거

#### 1. 안정성

- **분산 네트워크 기반**  
  블록체인은 단일 중앙 서버 없이 **P2P(Peer-to-Peer) 방식**으로 구동되는 구조입니다.  
  즉, 특정 서버만 공격해서는 전체 시스템을 무너뜨릴 수 없습니다.

- **노드 다수 해킹의 비현실성**  
  블록체인은 모든 노드에 동일한 거래 데이터를 저장합니다.  
  따라서 데이터를 변조하려면 절반 이상의 노드를 동시에 해킹해야 하지만 이는 **현실적으로 거의 불가능**하다고 평가됩니다.

- **데이터 무결성**  
  하나의 노드가 해킹을 당해도 다른 노드들과의 데이터 대조로 인해 변조가 쉽게 발견되고 원상 복구될 수 있습니다.

#### 2.익명성

- **계정 생성 시 신원 인증 불필요**  
  블록체인 네트워크에서 개인 계정을 발급받을 때, 별도의 **개인 정보 확인 또는 제3자 인증**이 필요하지 않습니다.

- **거래 내용 공개, 사용자 추적 난이도**  
  거래 기록 자체는 전부 공개되지만, 실제 사용자의 신원과 거래 내역을 직접 연결짓기 어렵습니다.  
  이로 인해 블록체인은 **익명성**을 어느 정도 보장하지만, 동시에 특정 사용자를 추적하는 것은 매우 까다롭습니다.

---
블록체인은 **“공공 거래장부”**, **“분산 거래장부”** 등으로 불릴 만큼 투명성과 안정성을 동시에 충족하는 독특한 기술입니다. 네트워크에 참여하는 모든 노드가 데이터를 공유하고, 서로 대조·검증하는 과정을 통해 **보안**과 **신뢰**를 확보합니다.


<br>

# 1️⃣ 기획 배경 / 개발 필요성
### ⚠ 문제점 분석

#### **1. 스타트업 투자 시장의 문제점**
- **비상장 스타트업 투자 정보 부족**
  - 투자하고 싶어도 관련 정보가 충분하지 않아 투자 판단이 어려움.
  
- **투자 구조 및 자금 흐름의 불투명성**
  - 투자 과정이 복잡하고, 투자 금액이 어디로 어떻게 흘러가는지 명확하지 않음.

- **높은 투자 진입 장벽**
  - 최소 투자 금액이 높아 일반 개인 투자자들이 쉽게 참여할 수 없음.

- **투자자 네트워킹의 어려움**
  - 투자자와 스타트업 간의 연결이 어렵고, 초기 스타트업은 실적 부족으로 투자 유치가 힘듦.

---

### 📊 조사 분석

#### **1. 스타트업 투자에 대한 접근성 문제**
- 스타트업 투자는 **고액 자본을 가진 투자자 중심으로 이루어짐**.
- 일반 대중이 참여하기에는 **최소 투자금이 너무 높고, 절차가 복잡**함.
- 개인투자자들이 스타트업에게 **투자할 수 있는 경로**가 거의 존재하지 않음.

📌 **관련 기사**  
[“벤처‧스타트업 숙원 BDC(개인투자자 자금기반 스타트업, 벤처 공모펀드)‘차일피일’ 도입 미뤄져”](https://www.m-i.kr/news/articleView.html?idxno=1052539)

#### **2. 자금 조달과 정책적 지원의 한계**
- 글로벌 고금리 기조로 인해 안전자산(예: 채권)에 대한 선호도가 높아지면서 **스타트업 투자 매력이 감소**
- **정부의 창업 및 초기 스타트업 지원 예산도 축소**되고 있어 정책적 마중물 역할이 약화. 이는 특히 초기 단계 스타트업 생태계에 부정적인 영향.

📌 **관련 기사**  
["벤처투자 시장 장기침체…초기 스타트업 소외 심화"](https://www.etnews.com/20240830000217)  

---

### ✨ 개발 필요성
Picktartup은 블록체인 기반 스타트업 조각 투자 플랫폼으로, 개인 투자자들이 소액으로도 스타트업에 투자할 수 있도록 지원합니다. 기존 스타트업 투자 시장의 정보 부족, 높은 진입 장벽, 자금 흐름 불투명성 등의 문제를 해결하고, 토큰증권(STO)을 활용한 지분 거래, 자동화된 투자 계약, 투명한 투자 관리 시스템을 제공합니다. 이를 통해 스타트업의 자금 조달 기회를 확대하고, 개인 투자자의 접근성을 향상시키는 것을 목표로 합니다.

<br>

# 2️⃣ 프로젝트 소개
### 🔔 핵심 포인트
1. 접근성 : **블록체인** 기반 토큰증권으로 개인투자자의 스타트업 투자 진입장벽 완화
2. 신뢰성 : 블록체인을 통한 **투명한 거래 기록** 보관 및 관리
3. 효율성 : 지분의 **토큰화**를 통한 소액투자 가능

🎯 기대 효과<br>
✔ 개인 투자자의 스타트업 투자 접근성 확대<br>
✔ 투명한 투자 환경 조성 및 신뢰도 향상<br>
✔ 스타트업의 자금 조달 기회 확대 및 생태계 활성화<br>

### 🎈 서비스
* 회원 관리 시스템
  * 자체 회원가입/로그인 기능
  * 마이페이지를 통한 회원정보 및 지갑주소 관리

* 블록체인 지갑 시스템
  * 개인별 지갑 생성 및 관리
  * 실시간 잔고 조회 및 토큰 거래 기능

* 토큰 관리 시스템
  * 결제 완료 시 자동 토큰 발행
  * 블록체인 네트워크 기반 실시간 잔고 업데이트

* 투자 계약 관리
  * 자동화된 계약서 생성 및 관리
  * 목표 미달성 시 자동 환불 시스템
  * 계약 진행상황 실시간 모니터링

* 코인 거래 시스템
  * 편리한 코인 구매 및 현금화 기능
  * 상세한 거래내역 조회 서비스

* 스타트업 정보 플랫폼
  * 키워드 기반 스타트업 검색
  * SSI(Start-up Success Index) 기반 투자 정보 제공
  * 상세한 기업 정보 열람 서비스

* 관리자 시스템
  * 실시간 시스템 자원 및 트래픽 모니터링 시스템
  * Kibana, Grafana 통합 모니터링 제공

<br>

## 🔎 상세 서비스 소개
**Landing Page**

PicktartUp에 접속하면 만날 수 있는 랜딩 페이지
![픽타트업_메인화면](https://github.com/user-attachments/assets/cc3a15c9-2d50-4063-b9ef-4f5b5b5225e0)


**회원가입 및 지갑생성**

회원가입과 동시에 Binance Network 기반의 지갑이 생성되며 해당 지갑의 지갑 비밀번호는 개인이 관리하도록 합니다.
![회원가입 및 지갑생성](https://github.com/user-attachments/assets/c8a15eb7-7308-4e06-aa06-f2609a1ab1e1)

**로그인**

로그인 이후 투자할 스타트업을 찾아 볼 수 있습니다.
![로그인](https://github.com/user-attachments/assets/5bd9b9e3-03f2-4943-b85e-c23d55b6e045)


**토큰결제 및 토큰발행**

토큰을 결제한 후 토큰이 발행되어 해당 유저의 지갑으로 전송됩니다.
![토큰결제 및 발행_v3](https://github.com/user-attachments/assets/c396ba57-c52d-469c-b183-11283092fa2e)

**스타트업 SSI지표**

스타트업의 재무현황, MAU, 고용인원, 자체적인 기준으로 스타트업의 성장지수를 보여주는 Smart Startup Index 지표(팀, 제품, 잠재성, 성과) 등 사용자의 투자에 도움될 수 있도록 지표를 제공합니다.
![SSI_지표_V4](https://github.com/user-attachments/assets/ece7a324-416a-46ba-abb3-e3d6f71d2f38)

**투자실행**

투자할 토큰을 입력 후 계약서를 읽고 서명하면 투자가 실행됩니다. 이후 스타트업이 지정한 금액만큼 모금이 완료되면 투자는 실행되고, 모금액이 모이지 않으면 토큰은 반환됩니다.
![투자하기_f1_v2](https://github.com/user-attachments/assets/70985bbf-cf72-43b7-b8f6-6019264cf925)


**투자내역 확인 및 계약서 확인**

투자한 스타트업의 모금현황 및 투자금액, 수익률, 계약서 등 상세한 내용을 확인할 수 있습니다.
![투자 상세내역 및 계약서 확인_f2](https://github.com/user-attachments/assets/de8e0580-0509-47e7-a599-df8a03adb83c)


**투자계약서 다운로드**

사용자는 투자한 스타트업에 대한 계약사항을 계약서로 다운로드 받을 수 있습니다.
![투자 계약서 다운로드_f3](https://github.com/user-attachments/assets/2858c46c-9375-42d2-ab13-d053b0f17647)


**투자알림 메일**

스타트업 대표는 투자 알림을 받을 수 있습니다.
![투자완료 메일_f4](https://github.com/user-attachments/assets/f4d161ea-6813-4232-aba1-6c2fbac982db)


**시스템 모니터링**

시스템 부하(CPU, Memory, IO), 네트워크, API 응답속도, 에러횟수, 트래픽 등 모니터링 시스템 구축을 통해 서비스 안정성을 확보하였습니다.


![30초_모니터링_f1 (1)](https://github.com/user-attachments/assets/5f608291-f50c-4f3d-98db-7bca4ee35bd0)

<br>

![30초_모니터링_f2](https://github.com/user-attachments/assets/5fafdd3b-afb5-406f-b690-a4adc68e6acd)



# 3️⃣ 인프라 아키텍처
**Amazon EKS 아키텍처**
![EKS_아키텍처_낮은용량](https://github.com/user-attachments/assets/b1417799-ecff-41f8-8be2-ff5eec20a6be)

---
## 🔐 전체 아키텍처 주요 구성 요소와 설계 의도
## 1. 네트워킹과 서비스 접근
### 1.1 ALB Ingress → Private Subnet에 있는 React App 접근
- **구현 방식**  
  - **ALB(Ingress Controller)** 를 사용해, 외부로부터의 HTTP/HTTPS 트래픽을 받아 **Private Subnet** 내의 Frontend React App Pod로 라우팅  
  - ALB는 Public Subnet(Internet-facing) 쪽에 위치하고, 실제 애플리케이션(React App)은 Private Subnet 내에서 동작
- **장점**  
  - **보안상 이점**: 프론트엔드 애플리케이션 자체가 Public IP로 직접 노출되지 않아 공격 표면이 줄어듬
  - **고가용성**: AWS ALB 자체가 Multi-AZ를 지원하며, 내부의 React App은 Kubernetes의 HPA, Cluster Autoscaler 등으로 스케일링 가능  
  - **기능 확장성**: 인증/인가, WAF 연동, Path-based 라우팅 등 ALB/Ingress 수준에서 설정 가능

### 1.2 NAT Gateway & VPC Endpoint 활용
- **NAT Gateway**  
  - Private Subnet에 있는 애플리케이션(Pod, EC2 등)이 Public 인터넷으로 나갈 때 사용  
  - 가용영역(AZ)마다 하나씩 배치하여 AZ 장애에 대비  
- **VPC Endpoint**  
  - S3, DynamoDB, ECR 등 AWS 내부 서비스 접근 시 NAT Gateway를 거치지 않고 **직접 VPC 내부 통신**  
  - **비용 절감** 및 **Latency 감소** 효과

---

## 2. MSA 아키텍처 & Kubernetes 선택 이유

### 2.1 마이크로서비스(MSA) 아키텍처의 필요성
- **독립 배포**: 각 서비스(Frontend, User, Coin, Startup 등)를 별도의 배포 파이프라인 및 스토리지로 운영해 장애 격리 및 빠른 릴리스 가능  
- **확장성**: 서비스별로 필요한 시점에만 확장/축소 가능 (HPA 활용)  
- **유지보수 편의**: 코드베이스와 DB가 독립되어 있어 스키마 충돌, 의존성 문제 최소화

### 2.2 Kubernetes(EKS) 기반 운영 장점
- **오토스케일링**: HPA로 Pod 수를 조절, 필요 시 Cluster Autoscaler로 노드 스케일링  
- **고가용성**: Multi-AZ에 걸쳐 노드를 분산 배치하여 장애 대응  
- **표준화된 생태계**: Helm, Operators 등 다양한 오픈소스 생태계 활용  
- **GitOps 파이프라인**: ArgoCD 등과 연계해 선언적 배포 자동화, 견고한 CI/CD 구축 용이

---


**On-prem K8s 아키텍처**
![On-premise-kubernetes-아키텍처_낮은용량](https://github.com/user-attachments/assets/6363733d-a118-4c71-b040-04561ab91cdd)


---


## 3. 데이터베이스 & 스토리지 구성

### 3.1 StatefulSet PostgreSQL in EKS
- **구현 방식**  
  - 각 마이크로서비스마다 **개별 StatefulSet**으로 PostgreSQL을 운영  
  - **PVC(Persistent Volume Claim)** 를 통해 EBS 볼륨을 마운트  
- **장점**  
  - **데이터 격리**: 마이크로서비스별로 스토리지 및 DB 스키마 분리  
  - **확장성/독립성**: 한 서비스의 DB 스키마 변경이 다른 서비스에 영향을 주지 않음  
- **보완점**  
  - RDS/Aurora 같은 매니지드 DB 고려 시 운영 비용 감소, 고가용성, 백업 자동화 가능
  - 다만 비용이 많이 들어서 도입 시 충분한 고민 필요.

### 3.2 온프레미스 사용 (Wallet, Contract 등)
- **보안/규제 이유**  
  - 민감한 데이터를 다루는 Wallet/Contract DB를 **온프레 K8s**에 유지  
  - Site-to-Site VPN으로 AWS와 연결  
- **NFS 기반 PVC**  
  - On-Prem K8s 클러스터에서 NFS를 통해 StatefulSet DB(Storage) 운영  
  - 비용 절감 및 자체 인프라 보안 정책 준수

---

## 4. 하이브리드 클라우드 연동

### 4.1 Site-to-Site VPN
- **구현 방식**  
  - 온프레미스와 AWS VPC 간 IPsec VPN을 구성해 안전한 사설 네트워크 연결  
  - 오픈소스 **Openswan** 기반의 가상 VPN 게이트웨이 사용  
- **장점**  
  - **데이터 주권/보안 준수**: 민감 정보나 규제 대상 데이터를 사내(온프레)에서 관리  
  - **비용 측면**: Direct Connect보다 설치·운영 비용이 낮고 구축이 단순

### 4.2 양쪽 K8s 간 역할 분담
- **AWS EKS**  
  - Public 트래픽 처리(Frontend, User, Coin, Startup 서비스 등)  
  - 높은 확장성과 자동화에 최적화  
- **On-Prem K8s**  
  - 민감 데이터 처리(Contract, Wallet), 무거운 모니터링 스택(Grafana, Prometheus, EFK), ArgoCD 등 운영  
  - 클라우드 리소스 비용 절감

---

<img width="811" alt="Image" src="https://github.com/user-attachments/assets/b6d4497c-be1c-4189-8d25-505e582319e2" />

<img width="1107" alt="image" src="https://github.com/user-attachments/assets/f76b3250-dec2-45d6-8738-7d1a7a26922f" />

## 5. CICD & 운영 자동화

<img width="1314" alt="Image" src="https://github.com/user-attachments/assets/4d284aec-9965-4a7c-86c2-51256de98909" />

### 5.1 Jenkins & ArgoCD 연계 (GitOps)
- **흐름**  
  - **코드 변경 발생** → Jenkins가 Build & Test → Docker 이미지를 ECR로 푸시  
  - **GitOps 저장소 업데이트:** 매니페스트에 정의된 **이미지 태그변경** → ArgoCD가 감지해 EKS 또는 On-Prem K8s에 자동 반영  
- **장점**  
  - **자동화**: 사람이 수동으로 커맨드를 실행하지 않아도, 코드 업데이트부터 배포까지 일관된 파이프라인  
  - **추적성**: Git 커밋 히스토리로 인프라/애플리케이션 상태를 추적 가능

### 5.2 Jenkins & Redis를 EC2로 배포한 이유
- **비용 효율**: 쿠버네티스 노드/Pod로 운영할 만한 스케일이나 오토스케일링 필요가 크지 않음  
- **운영 단순화**: EC2 예약 인스턴스/세이빙 플랜 등으로 일정한 비용 관리, Jenkins 관리가 독립적

---

## 6. 모니터링 & 로깅

### 6.1 Prometheus, Grafana, EFK Stack (On-Prem)
- **구현 방식**  
  - 온프레미스 K8s에 **Grafana, Prometheus, ElasticSearch, Fluentd, Kibana** 배포  
  - 클라우드/온프레 모든 K8s 클러스터의 로그, 메트릭을 중앙 수집  
- **이점**  
  - **클라우드 비용 절감**: AWS Managed Prometheus, OpenSearch Service를 쓰는 대신 온프레 자체 리소스로 운영  
  - **분석/시각화**: ElasticSearch + Kibana로 로그를, Prometheus + Grafana로 메트릭을 통합 시각화

### 6.2 주의점
- **VPN 대역폭**: 클라우드에서 발생하는 로그/메트릭이 온프레로 전송되므로 VPN의 트래픽 용량과 안정성 지속 모니터링  
- **보안**: 로그 내 민감 데이터나 접근 권한 설정을 사전에 철저히 제어

---

## 7. 종합 평가 및 장점

1. **보안 및 고가용성**  
   - Multi-AZ 구성, Private Subnet에서의 Pod 운영, 네임스페이스 단위 격리, VPN 연결 등으로 안정성과 보안성이 높음

2. **비용 최적화**  
   - VPC 엔드포인트 활용으로 NAT Data Transfer 비용 절감  
   - 온프레미스에 무거운 모니터링/로그 시스템을 둬서 클라우드 비용 절감  
   - Jenkins/Redis EC2 운영을 통해 불필요한 K8s 리소스 낭비 최소화

3. **유연한 확장성**  
   - HPA, Cluster Autoscaler로 서비스 부하 변화에 따른 자동 스케일링  
   - ArgoCD를 통한 GitOps로 지속 배포, 코드 변경 시 빠른 적용

4. **하이브리드 전략의 균형**  
   - 클라우드의 확장성, 온프레의 보안·비용 강점을 잘 활용  
   - 민감 데이터(Contract, Wallet) 온프레 유지, 대외 서비스(Frontend, User, Coin, Startup)는 클라우드에서 운영

---

### 🤔 앞으로 고려할 만한 사항

- **DB 운영 고도화**: StatefulSet PostgreSQL 백업/복구 자동화, RDS/Aurora 대안 검토  
- **DR(Disaster Recovery) 전략**: 멀티리전 또는 온프레–클라우드 간 상호 백업/Failover 정책 정교화  
- **네트워크 정책**: Calico/NetworkPolicy와 보안 그룹을 조합한 세밀한 접근제어 관리 
- **로그 트래픽 최적화**: VPN 대역폭 감당 가능성 점검

---


<br>

# 4️⃣ 기술스택
![image](https://github.com/user-attachments/assets/27c2b530-80b7-41ce-9287-05fca37e3897)

---

### 1) IDE
- **IntelliJ IDEA**: SpringBoot 백엔드 개발 IDE로 사용
- **Visual Studio Code**: React 프론트엔드 개발 IDE로 사용
- **Spring Tool Suite(STS) 또는 Eclipse**: 스프링 프레임워크 기반 개발에 특화된 IDE (Eclipse 기반)

---

### 2) Cooperation (협업 툴)
- **Jira** (혹은 Trello): 이슈 트래킹 & 데일리 스크럼 등의 프로젝트 관리 도구로 사용 
- **Slack**: 팀 커뮤니케이션용 메신저로 사용
- **Notion**: 문서 정리, 위키, 작업 관리 등을 통합적으로 관리
- **Figma**: UI/UX 디자인 및 프로토타이핑 제작에 사용

---

### 3) FrontEnd
- **React**: 페이스북(메타)에서 만든 대표적인 프론트엔드 라이브러리 프론트앤드 개발에 사용
- **Tailwind CSS**: 유틸리티 퍼스트(Utility-first) 방식의 CSS 프레임워크  

---

### 4) BackEnd
- **Spring Boot**: 자바/코틀린으로 서버 사이드 애플리케이션을 만들 때 주로 사용되는 스프링 기반 프레임워크 백엔드 개발에 사용
- **Sring Data JPA**: 일반적으로 Spring Boot 기반 애플리케이션에서 ORM으로 많이 쓰이는 스프링 모듈

---

### 5) BlockChain
- **Solidity**: BSC 스마트 컨트랙트 개발을 위해 사용
- **Binance Smart Chain(BSC)**: 바이낸스에서 운영하는 이더리움 호환 블록체인  
- **Truffle**: 이더리움/BSC DApp 개발 및 테스트를 위한 툴/프레임워크

---

### 6) Database
- **MongoDB**: 뉴스기사, 거래 데이터 등 비정형데이터 저장을 위해 사용
- **Flyway**: 데이터베이스 마이그레이션/스키마 통일 용도로 사용
- **PostgreSQL**: 병렬 테이블 풀스캔, 포인트 인 타임 복구 등의 이점으로 PostgreSQL DB 채택
- **Redis**: 레이스컨디션 이슈 해결, JWT 리프레시 토큰, API 캐싱 등 사용
- **Amazon S3**: 이미지, PDF 바이너리 파일 저장용

---

### 7) Infra (인프라/환경 구성)
- **Containerd**: 쿠버네티스 CRI(Container Runtime Interface)로 사용
- **Kubernetes(K8s)**: 컨테이너 오케스트레이션 도구  
- **Nginx**: 웹 서버/리버스 프록시/로드 밸런서 온프레미스 Ingress Controller로 사용
- **Terraform**: EKS 클러스터 생성, 삭제 반복작업 자동화 목적으로 사용 
- **Amazone EKS**: HPA, Cluster Autoscaler 자동 프로비저닝 목적으로 사용

---

### 8) CI/CD
- **Jenkins**: 각 백엔드 마이크로서비스 레포지토리 변경 시 CI 작업 자동화  
- **ArgoCD**: 레포지토리 커밋 업데이트 시 배포중인 매니페스트의 이미지 태그도 변경되어 K8s 클러스터 CD 자동화

---

### 9) Monitoring
- **Prometheus**: Helm을 통해 프로메테우스 스택 배포 Node Exporter 메트릭 수집 
- **Grafana**: 데이터 시각화 및 대시보드로 활용
- **Fluent Bit**: DaemonSet으로 로그 수집/처리 Elasticsearch로 실시간 로그전송 
- **Elasticsearch** + **Kibana**: 로그/문서 검색 엔진(Elasticsearch)과 시각화 대시보드(Kibana) 활용

---



# 5️⃣ 협업방식

### ⏳ 개발일정
![image](https://github.com/user-attachments/assets/c95bea34-4bac-4e84-af55-6c06a45c3f45)
애자일 방법론은 시장 변화에 유연하게 대응하며 지속적인 업데이트와 사용자 피드백을 반영하는 것을 목표로 합니다. 하지만 저희는 교육 과정 프로젝트의 정해진 마감 기한이라는 제약 조건 때문에 폭포수 모델에 가까운 개발 방식을 따를 수밖에 없었습니다. 그럼에도 불구하고, 향후 실무 환경의 애자일 문화에 적응하기 위해 팀 내에서는 데일리 스크럼, 백로그 관리 등 애자일 실천 방법(practices)을 일부 도입하여 개발 일정을 관리했습니다.



### 👨🏻‍💻 노션협업
![Image](https://github.com/user-attachments/assets/1ef9c8d0-459c-4974-a078-7e8927501e3a)

![Image](https://github.com/user-attachments/assets/232cccba-343d-43bc-8731-59cc66882460)
- 협업에 필요한 자료(개인 기술공부, 회의록, 담당 업무별 문서정리, 업데이트 노트)등을 노션 원페이지에 정리하여 생산성을 높였습니다.
- 데일리스크럼을 통해 담당한 업무의 진행상황과 이슈를 공유하여 신속하고 유연하게 문제를 해결했습니다.
### 🍎 백로그 관리
#### 요구사항 정의하기
![Image](https://github.com/user-attachments/assets/572a43f2-00fe-498c-88f0-d23f73c9f209)


#### 사용자 스토리 형식에 맞추기
사용자 스토리(User Stories)
- 누가(Who): 사용자 또는 이해관계자
- 어떻게(How): 사용자가 원하는 기능이나 작업을 수행하는 방법
- 무엇을(What): 기능의 결과나 이점
  
![Image](https://github.com/user-attachments/assets/eb49aa5d-3be3-41a8-b6c4-7da6460628e2)

#### 담당자 및 스토리 포인트 지정
![Image](https://github.com/user-attachments/assets/952e2983-0f4d-4ec3-b464-32a9399409aa)

#### 세부 시나리오 작성
![Image](https://github.com/user-attachments/assets/4e46f52f-6dc6-4313-b485-2ecdc0346ae2)

백로그는 사용자 스토리 형식으로 Jira에서 관리되었습니다. 사용자 스토리는 "~로서, ~기능을 원한다, ~때문에" 형식으로 작성되어 기능 개발의 목적과 사용자 가치를 명확하게 정의하는 데 집중했습니다.  

### 🌲 브랜치 전략(git flow)
![Image](https://github.com/user-attachments/assets/fca3e244-641e-4c58-80a9-1799255c38a6)
- **develop**: 개발 단계에서 통합된 브랜치로, 각 서비스별 기능 브랜치에서 merge됩니다.
- **feature/[서비스이름]/[기능이름]**: 각 기능 개발을 위한 브랜치입니다. 예를 들어, `feature/coin/exchange`와 같은 방식으로 서비스와 기능을 구분하여 브랜치를 생성할 수 있습니다.
- **release/[서비스이름]/[버전]**: 배포 준비가 완료된 브랜치로, 테스트 후 main에 merge됩니다.
---
팀 프로젝트라는 제한적인 환경 속에서도 Git-flow 전략의 이점을 최대한 활용하고자 노력했습니다. 실무처럼 지속적인 통합 및 배포(CI/CD)를 통한 실시간 서비스 제공은 어려웠지만 프로젝트 기간 내 완성도 높은 결과물을 만드는 것을 목표로 삼았습니다.

이러한 상황에서 hotfix, main 브랜치 운영은 현실적으로 어려웠지만 각 마이크로서비스(MSA) 저장소별로 feature, develop, release 브랜치를 활용하여 통합 테스트를 진행했습니다. 이를 통해 Git-flow의 핵심적인 협업 프로세스를 경험하고, 버전 관리 시스템을 체계적으로 활용하는 방법을 익힐 수 있었습니다.


#### ✈️ 이모지 커밋 컨밴션 정의


| 타입 | 설명 | 이모지 |
| --- | --- | --- |
| `feat` | 새로운 기능 추가. | ✨ |
| `fix` | 버그 수정. | 🐛 |
| `docs` | 문서 수정 (예: README, API 명세 등). | 📋 |
| `style` | 코드 포맷 변경, 세미콜론 누락 등 기능 변경이 없는 수정. | 🎨 |
| `refactor` | 코드 리팩토링 (기능 변화 없이 코드 구조 개선). | ♻️ |
| `test` | 테스트 코드 추가 또는 수정. | ✅ |
| `chore` | 빌드 작업, 패키지 매니저 설정 등 기타 자잘한 작업. | ✏️ |
| `perf` | 성능 개선 | ⚡️ |
| `ci/cd` | 배포 커밋 | 👷 |
| `test` | 테스트 코드 수정에 대한 커밋 | ✅ |
| `init` | 최초 프로젝트 업로드 | 🐣 |
| `build` | 빌드 파일 변경 | 🔧 |

> 이모지 + 뛰어쓰기 + 소문자: 한글로 설명

<img width="1320" alt="Image" src="https://github.com/user-attachments/assets/edd638ff-4b7e-4143-a232-76324bdb2e58" />

🙂 이모지를 사용하여 커밋 컨밴션을 정의한 이유는 시각적 효과를 높이고, feat: 설명 과 같이 명확한 형식을 통해 커밋 내용을 빠르게 파악하여 협업 효율성을 높이고자 했습니다.

### 📌 Issue / Pull Request 협업


<img width="932" alt="Image" src="https://github.com/user-attachments/assets/63d964a4-5de3-479a-b0a4-f46198c60754" />

<img width="1306" alt="Image" src="https://github.com/user-attachments/assets/90f67599-ed1d-4759-8de2-099f71a6d4d6" />

Issue와 Pull Request를 적극 활용하여 프로젝트의 진행 상황을 투명하게 공유하고, 각 작업 단계를 체계적으로 관리하며, 팀원 간의 효율적인 의사소통을 이끌어냈습니다.

# 6️⃣ 개발 플로우

### 📝 린캔버스 작성
![Image](https://github.com/user-attachments/assets/5897c5cf-45f2-47de-88b1-a11a9a54fa80)
![Image](https://github.com/user-attachments/assets/3533ae86-d05d-4025-8ac4-112234232f83)

린캔버스는 비즈니스 모델의 핵심 요소를 빠르게 검증하고, 아이디어 실현 가능성을 높이기 위해 팀원들과 의견을 나누며 기획단계에서 상세히 작성하였습니다.



### 🔎 프로세스 다이어그램

![Image](https://github.com/user-attachments/assets/a052ba2a-bb2c-4803-ab0e-ba7b44936c07)
![Image](https://github.com/user-attachments/assets/b1aa4031-23dd-405e-b56b-c7e7da3d2a59)

복잡한 요구사항을 시각화된 다이어그램으로 팀원 간의 이해도를 높이고, 모든 팀원이 동일한 이해를 바탕으로 개발에 참여하기 위해 프로세스 다이어그램을 설계하였습니다.
### 🗒️ 사용자 인터페이스
![Image](https://github.com/user-attachments/assets/a190f1d0-802c-4966-8bd5-f00a1ec900f9)

<img width="727" alt="Image" src="https://github.com/user-attachments/assets/8eabdeda-e12b-48e6-8b87-2e38cae856d9" />

사용자 인터페이스 정의와 Figma를 이용하여 직관적인 인터페이스를 만들고, 개발효율성을 높이며 팀원들 간의 원활한 소통을 위해 설계하였습니다.


### 시퀀스 다이어그램
![Image](https://github.com/user-attachments/assets/df7d2cdb-daff-4257-a88a-b9798d054a80)

![Image](https://github.com/user-attachments/assets/ec1d2131-14b0-4518-b3d9-69149ff8032a)

![Image](https://github.com/user-attachments/assets/f44f7193-6462-4a46-805b-d45e9c31a0a0)

시퀀스 다이어그램을 통해 복잡한 시스템의 상호 작용과 데이터 흐름을 명확하게 표현하여 개발 과정의 이해도를 높여 효율적인 개발을 가능하게 했습니다.

# 7️⃣ 팀소개
## 👩‍💻👨‍💻 팀 소개

| 구분  | 이름   | 역할  | 깃허브 주소  |
|------|------|------|------------|
| 팀장  | 최영하 | 인프라 아키텍처 설계 및 구축, CI/CD 파이프라인 구현 | [GitHub](https://github.com/ChoiYoungHa) |
| 팀원  | 허예은 | 토큰결제, 계약서 생성 기능구현 | [GitHub](https://github.com/yyyeun) |
| 팀원  | 류채현 | 유저 관리 기능 구현, 토큰생성 및 계약 기능 구현 | [GitHub](https://github.com/RyuChaeHyun) |
| 팀원  | 최나영 | 스타트업 기능 구현, SSI 지표구현 | [GitHub](https://github.com/na-rong) |
| 팀원  | 구동길 | Site to Site VPN 구현, 퍼블릭 네트워크 설정 | [GitHub](https://github.com/dkac0012) |


### 역할상세
- 최영하
    - 인프라 아키텍처 설계
        - EKS 구축
            - AWS VPC 설계
            - VPC, ALB, EKS, IAM 테라폼 자동화
            - EKS ServiceAccount 권한설정
            - Cluster Autoscaler 설정 및 HPA 설정
        - On-Prem K8s 구축
            - kubeadm K8s 구축 Ubuntu 22.0 VM(master), VM1~3(Worker) 생성
            - Sealed-Secret 생성 및 관리
        - 네임스페이스별 마이크로서비스 분리 및 RBAC 정책관리
        - Redis, Jenkins, ArgoCD 구축
            - Jenkins 파이프라인 작성
        - ALB, Nginx Ingress 트래픽 라우팅 구축
            - ALB Ingress SSL 적용
        - Statefulset PostgreSQL 구축 및 flyway 스키마 마이그레이션 자동화
  - CI/CD 파이프라인 구축
      - Jenkins + ArgoCD GitOps 기반 멀티클러스터 CI/CD 구축
  - API 설계
      - ContractService(계약서비스) API 설계
  - 모니터링 파이프라인 구축
      - Elasticsearch, FluentBit, Prometheus 매트릭 수집 파이프라인 구축
      - Grafana, Kibana 대시보드 구축
- 허예은
    - 토큰결제
        - 포트원 API를 활용한 PG사 결제 시스템 구현
        - 잔여 코인 조회 기능
        - 코인 구매 내역 조회
        - 잔여 코인 조회 기능
    - 계약서 서명
        - 계약서 서명 기능구현
    - Jenkins EC2 마이그레이션
        - 기존 t2.micro → EC2 t2.medium으로 마이그레이션
    - 계약서 생성
        - 유저, 스타트업, 스마트 컨트랙트 정보를 바탕으로 계약서 PDF를 생성
        - 계약서 생성 후 S3 버킷에 업로드
    - 토큰조회, 계약서 조회, 토큰 결제, 계약서 서명 프론트앤드 개발
- 류채현
    - BNB 스마트컨트랙트 기능개발
        - solidity를 이용한 BSC 테스트넷 스마트컨트랙트 기능 개발
        - BNB 코인을 Fork하여 PKN 토큰발행
    - 유저 서비스 개발
        - SpringSecurity JWT 토큰 인증 개발
            - Redis Refresh Token 및 블랙리스트 기능 개발
    - 지갑 서비스 개발
        - 회원가입 시 BSC 네트워크에서 개인 지갑생성
    - 모니터링 시스템 프론트앤드 개발
        - 통합 모니터링 페이지 프론트앤드 개발
- 최나영
    - 스타트업 서비스 개발
    - SSI 지표 연구 및 개발
        - 자체적으로 스타트업의 가치를 평가하는 SSI 지표 개발
        - 프론트앤드 그래프 시각화 및 데이터 크롤링
    - 뉴스기사 크롤링
        - 스타트업 관련 기사 크롤링하여 MogoDB에 적재
        - 스타트업 상세 페이지 프론트앤드 개발
    - Elasticsearch 검색기능 개발
        - Logstash 파이프라인 구축
    - 메인페이지 프론트앤드 개발
    - 발표 동영상 제작
- 구동길
    - Site to Site VPN 개발
        - On-Prem에 오픈스완 VM을 생성하여 가상 VPN 장비구축
        - AWS VPN 사용을 위한 CGW,VGW,ACL 구축
    - Jmeter를 활용한 On-prem 클러스터에 스트레스 테스트
        - CPU, 네트워크 매트릭 임의 테스트
    - 발표자료 제작







