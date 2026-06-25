# RSS 기반 AI 기술 뉴스 자동 수집 및 요약 시스템

<p align="center">

![Make](https://img.shields.io/badge/Make-Automation-6D5DF6)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4)
![Stability AI](https://img.shields.io/badge/Stability-AI-000000)
![Notion](https://img.shields.io/badge/Notion-Database-000000)
![Google Drive](https://img.shields.io/badge/Google-Drive-34A853)
![Discord](https://img.shields.io/badge/Discord-Webhook-5865F2)

</p>

<p align="center">

![Status](https://img.shields.io/badge/Status-Completed-success)
![Version](https://img.shields.io/badge/Version-v1.0-blue)
![Team](https://img.shields.io/badge/Team-6_Members-orange)

</p>

---

## 프로젝트 소개

본 프로젝트는 RSS를 활용하여 최신 AI 기술 뉴스를 자동으로 수집하고, Google Gemini를 이용하여 기사 요약 및 감성 분석을 수행한 뒤 AI 썸네일 이미지를 생성하여 Notion 데이터베이스에 자동 저장하는 Make 기반 자동화 시스템입니다.

또한 URL 기반 중복 기사 제거, 하루 1건 저장 정책, Webhook 기반 API 재시도, Discord 오류 알림 기능을 적용하여 실제 운영 환경을 고려한 안정적인 자동화 워크플로우를 구현하였습니다.

---

# 프로젝트 목표

- 최신 AI 기술 뉴스 자동 수집
- 생성형 AI를 활용한 뉴스 요약 자동화
- AI 기반 뉴스 썸네일 생성
- Notion 데이터베이스 자동 관리
- 반복 업무 자동화를 통한 정보 수집 효율 향상

---

# 핵심 기능

| 기능 | 구현 |
|------|:---:|
| RSS 자동 수집 | ✅ |
| AI 기사 자동 필터링 | ✅ |
| Google Gemini 뉴스 요약 | ✅ |
| 감성 분석 | ✅ |
| AI 이미지 생성 | ✅ |
| Google Drive 저장 | ✅ |
| Notion 자동 저장 | ✅ |
| URL 기반 중복 제거 | ✅ |
| 하루 1건 저장 | ✅ |
| Gemini 최대 2회 재시도 | ✅ |
| Discord 오류 알림 | ✅ |
| 전 과정 자동 실행 | ✅ |

---

# 시스템 구조

## 메인 시나리오

![메인 시나리오](images/workflow_main.png)

---

## 하위 시나리오

![하위 시나리오](images/workflow_sub.png)

---

# 기술 스택

| 분야 | 사용 기술 |
|------|-----------|
| 자동화 플랫폼 | Make |
| 생성형 AI | Google Gemini |
| 이미지 생성 | Stability AI |
| 데이터 저장 | Notion Database |
| 이미지 저장 | Google Drive |
| RSS 관리 | Google Sheets |
| 오류 알림 | Discord |
| 통신 | HTTP / Webhook |

---

# 프로젝트 구조

```text
AI-RSS-News-Automation
│
├── README.md
│
├── docs
│   ├── 01_project_planning.md
│   ├── 02_workflow_description.md
│   ├── 03_project_decision_log.md
│   └── 04_project_result.md
│
└── images
    ├── workflow_main.png
    ├── workflow_sub.png
    ├── filter_result.png
    ├── gemini_result.png
    ├── json_parse.png
    ├── thumbnail_result.png
    ├── drive_result.png
    ├── notion_result.png
    └── discord_error.png
```

---

# 프로젝트 문서

| 문서 | 설명 |
|------|------|
| 📄 01_project_planning.md | 프로젝트 기획서 및 팀 역할 |
| 📄 02_workflow_description.md | 워크플로우 구성 및 모듈 설명 |
| 📄 03_project_decision_log.md | 프로젝트 기획 및 의사결정 기록 |
| 📄 04_project_result.md | 실행 결과 및 테스트 보고서 |

---

# 구현 결과

### Notion 자동 저장 결과

![Notion Result](images/notion_result.png)

RSS에서 수집한 AI 기술 뉴스가 Google Gemini를 통해 요약 및 감성 분석된 후 AI 썸네일과 함께 Notion 데이터베이스에 자동 저장되는 것을 확인하였다.

> 자세한 테스트 결과 및 검증 과정은 **docs/04_project_result.md** 문서를 참고한다.

---

# 프로젝트 성과

- RSS 기반 최신 AI 기술 뉴스 자동 수집 구현
- Google Gemini 기반 뉴스 요약 및 감성 분석 자동화
- Stability AI 기반 뉴스 썸네일 자동 생성
- Google Drive 자동 업로드 및 공유 링크 생성
- Notion 데이터베이스 자동 저장
- URL 기반 중복 기사 제거
- 하루 1건 저장 정책 구현
- Webhook 기반 최대 2회 API 재시도
- Discord 오류 알림 기능 구현
- 사람의 개입 없이 전체 프로세스 자동 실행

---

# 향후 개선 사항

- RSS 뉴스 소스 확대
- AI 키워드 자동 추천 기능
- 기사 중요도 자동 분류
- Slack 및 이메일 알림 연동
- 주간·월간 뉴스 리포트 자동 생성
- 다국어 뉴스 번역 기능 추가

---

# Team

| 역할 | 담당 |
|------|------|
| 팀장 | 이원일 |
| 팀원 | 김호연 |
| 팀원 | 조경학 |
| 팀원 | 최주현 |
| 팀원 | 위홍빈 |
| 팀원 | 김민수 |

---

## 프로젝트 문서 바로가기

# 프로젝트 문서

- 📄 [01. 프로젝트 기획서](01_project_planning.md)
- 📄 [02. 워크플로우 설명서](02_workflow_description.md)
- 📄 [03. 프로젝트 기획 및 의사결정](03_project_decision_log.md)
- 📄 [04. 실행 결과 및 테스트 보고서](04_project_result.md)
