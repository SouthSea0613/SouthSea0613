# 김남해 — 인프라 하는 풀스택

**Backend · DevOps · Security** · 실서비스 인프라를 단독 운영하며, 실측 수치로 결과를 증명합니다.

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

### 실측 성과

| 지표 | 개선 전 | 개선 후 |
|---|---|---|
| 트래픽 10배 급증 대응 | 에러율 최대 2.9% | **에러율 0.008~0.05% · p95 0.3초** |
| 배포 시간 | 수동 배포 16분 | **CI/CD 8분** |
| 에러 가시성 | 무경보 (22.6만 건 잠복) | **경보·메트릭 필터 39개 · 대시보드 12개** |
| 보안 | 수기 대응 | **SIEM 구축 · ISMS-P 자체 감사 (취약점 72건 식별)** |

### 만들어 온 파이프라인

```mermaid
flowchart LR
  A["이벤트<br/>로그 · 에러 · 트래픽"] --> B["수집 · 판정<br/>SIEM · 메트릭 필터"]
  B --> C["알림<br/>SNS 경보 · 결재/소명"]
  C --> D["대시보드<br/>임원 · 운영 관제"]
  D --> E["개선 실측<br/>Cost Explorer · k6"]
```

**Portfolio** · [team.haeyounglab.com/Namhae_Kim](https://team.haeyounglab.com/Namhae_Kim) · **Contact** · tksz0613@gmail.com
