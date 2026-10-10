<div align="center">

**5년차 백엔드 개발자**

[![Email](https://img.shields.io/badge/Email-tjsal89000@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tjsal89000@gmail.com)

</div>

---

## 🛠 Tech Stack

**Backend**<br>
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Database · Messaging**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Infra · Cloud**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Monitoring**<br>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

## 🚀 개인 프로젝트

> 직접 설계하고, 부하테스트와 동시성 검증까지 해 본 프로젝트입니다.

### 🔹 [Payment AIOps Platform](https://github.com/tjsal89000/2026_-Portfolio)
가상 결제 트래픽을 실시간으로 흘려 **이상 징후를 자동 탐지**하고, AI가 운영 리포트를 작성하는 폴리글랏 관제 플랫폼
- Java(결제 API·Kafka 소비자) / Python(트래픽 생성·이상 탐지·AI 리포트) / TypeScript(게이트웨이·대시보드)를 언어별 강점에 맞게 배치
- Kafka(영속 이벤트 로그)와 Redis(실시간 카운터·Pub/Sub)의 역할 분리
- k3s, Terraform(AWS·OCI), Prometheus·Grafana·Tempo 분산 트레이싱, n8n 자동화

### 🔹 Ticketing Concurrency Platform
"같은 좌석을 수백 명이 동시에 누르면?"을 **세 가지 락 전략으로 구현하고 측정**한 프로젝트
- 비관적 락 / 낙관적 락 / Redis 분산락(Redisson) 비교. 50명 동시 요청에서 세 전략 모두 정확히 1명만 성공
- k6 부하테스트로 전략별 처리량·p95 실측 (낙관적 락 2,738 req/s, 비관적 락만 커넥션 고갈로 2% 실패)
- 가상 크레딧 결제·환불을 조건부 UPDATE로 구현해 동시 이중 결제·이중 환불 방지
- Java 17, Spring Boot 4, JPA, PostgreSQL, Redis, k6

---

<div align="center">

**"구축 과정은 반드시 문서로 남긴다"** 를 개발 문화의 기본으로 삼고 있습니다.

</div>
