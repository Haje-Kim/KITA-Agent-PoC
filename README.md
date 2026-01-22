# KITA Agent PoC - 무역 데이터 분석 플랫폼

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://haje-kim.github.io/KITA-Agent-PoC/)

한국무역협회(KITA)의 최신 무역통계와 AI 에이전트 기술이 결합된 시장 분석 플랫폼의 프로토타입입니다.

## 🚀 프로젝트 개요

이 프로젝트는 화장품 수출 기업을 대상으로 한 맞춤형 시장 분석 및 상담 플랫폼입니다.
AI 에이전트가 고객의 니즈에 맞춰 실시간 데이터 분석, 시장 리포트 생성, 그리고 전문가 상담 연계를 제공합니다.

## 📄 주요 파일 구조

```
KITA-Agent-PoC/
├── landing.html                          # 메인 랜딩 페이지 (시나리오 선택)
├── ai_agent_interface_scenario1.html      # 시나리오 1: 데이터 분석 상담
├── ai_agent_interface_scenario2.html      # 시나리오 2: 레포트 생성 요청
├── market_analysis_report.html            # 시장 분석 보고서 템플릿
└── README.md                              # 이 파일
```

## 🎯 주요 시나리오

### 시나리오 1: 데이터 분석 상담 💡
귀사의 수출 데이터를 분석하고, 미국 및 남미 시장의 유망성을 평가받는 상담입니다.

**주요 내용:**
- 기업 프로필 분석 및 실적 요약
- 시장 데이터 시각화 (차트 및 표)
- 미국 K-뷰티 시장 성장 배경 분석
- 남미 시장 진출 전략 제시
- 전문가 상담 연계 (TradePro, KITA POST 등)

**진입 링크:** [시나리오 1 시작](https://haje-kim.github.io/KITA-Agent-PoC/ai_agent_interface_scenario1.html)

### 시나리오 2: 레포트 생성 요청 📄
AI 에이전트가 귀사의 요청에 따라 맞춤형 시장 분석 레포트를 생성하고 이메일로 발송합니다.

**주요 내용:**
- 레포트 생성 요청 및 동의 프로세스
- 데이터 점검 항목 확인 (체크리스트)
- 분석 진행 상황 추적
- 레포트 발송 완료 알림
- 추가 Q&A 및 상담 유도

**진입 링크:** [시나리오 2 시작](https://haje-kim.github.io/KITA-Agent-PoC/ai_agent_interface_scenario2.html)

## 📊 시장 분석 보고서

2026년 미국 K-뷰티 기초화장품 수출 유망 품목을 분석한 전문 보고서입니다.

**보고서 내용:**
- 미국 시장에서의 K-뷰티 부상 배경
- 2025년 미국향 기초화장품 수출 동향
- 미국 MoCRA 규제 변화와 기업 영향
- 틱톡 기반 K-뷰티 소비 트렌드
- 미국 주요 유통망 내 K-뷰티 확산
- 시사점 및 전략 제언

**보고서 링크:** [시장 분석 보고서](https://haje-kim.github.io/KITA-Agent-PoC/market_analysis_report.html)

## 🌐 라이브 데모

이 프로젝트는 GitHub Pages를 통해 온라인에서 바로 체험할 수 있습니다.

**메인 페이지:** https://haje-kim.github.io/KITA-Agent-PoC/

## 💡 주요 기능

### 데이터 시각화
- Chart.js를 활용한 실시간 차트 및 그래프
- 수출 동향, 국가별 점유율, 시장 규모 등 시각화

### 인터랙티브 UI
- AI 메시지와 사용자 메시지 구분 (아바타 아이콘)
- 체크리스트, 프로세스 인디케이터 등 다양한 UI 요소
- CTA 버튼을 통한 외부 서비스 연계

### 반응형 디자인
- 모바일, 태블릿, 데스크톱 최적화
- 다양한 해상도에 대응하는 레이아웃

### 전문가 상담 연계
- TradePro 전문위원 상담 신청
- KITA POST 해외진출 컨설팅
- TradeKorea 바이어 매칭

## 🛠️ 기술 스택

- **Frontend:** HTML5, CSS3, JavaScript
- **Chart Library:** Chart.js
- **호스팅:** GitHub Pages
- **버전 관리:** Git

## 📝 CTA 버튼 연결

프로젝트 내의 모든 CTA 버튼은 다음 서비스로 연결됩니다:

| 버튼명 | 링크 |
|--------|------|
| TradePro 전문위원 상담 신청 | https://kita.net/tradePro/oneOnOneConsult/oneOnOneConsultList.do |
| 보고서 바로가기 | https://www.kita.net/researchTrade/report/tradeBrief/tradeBriefDetail.do?no=2907 |
| KITA POST 컨설팅 신청 | https://www.kita.net/kitaPost/kitaPostList.do |
| TradeKorea 바이어 검색 | https://kr.tradekorea.com/seller/buyer/buyerMatching.do |

## 🎨 디자인 특징

- **색상 체계:** 그라데이션 (보라색: #667eea → #764ba2)
- **타이포그래피:** 시스템 폰트 (Apple System Font, Segoe UI 등)
- **UX 패턴:** 챗봇 스타일의 대화형 인터페이스

## 📌 주요 구현 내용

### landing.html
- 프로젝트 소개 및 시나리오 선택
- 2개 시나리오의 상세 설명 및 링크
- 전체 프로젝트의 진입점

### Scenario 1: ai_agent_interface_scenario1.html
- 8단계의 AI-사용자 대화 플로우
- Chart.js를 활용한 데이터 시각화
- 통계 테이블 및 인사이트 박스
- 전문가 상담 연계 버튼

### Scenario 2: ai_agent_interface_scenario2.html
- 6단계의 레포트 생성 프로세스
- 체크리스트 및 상태 박스 UI
- 프로세스 인디케이터
- 리포트 바로가기 버튼

### market_analysis_report.html
- 전문적인 보고서 템플릿
- 목차 및 Executive Summary
- 7개 섹션의 상세 분석 콘텐츠
- 인쇄 최적화

## 📱 사용자 인터페이스

- **AI 아이콘:** 🤖 (로봇 이모지)
- **사용자 아이콘:** U (파란색 배경)
- **메시지 정렬:** 좌측(사용자) ↔ 우측(AI)
- **상호작용:** 클릭 가능한 버튼, 링크, 입력창

## 🔗 관련 링크

- **GitHub Repository:** https://github.com/Haje-Kim/KITA-Agent-PoC
- **Live Demo:** https://haje-kim.github.io/KITA-Agent-PoC/
- **한국무역협회:** https://www.kita.net

## 📄 라이선스

이 프로젝트는 한국무역협회의 교육 및 시연 목적으로 개발되었습니다.

---

**제작일:** 2026년 1월 22일
**제작자:** Claude Code (Anthropic)
**프로젝트 상태:** Proof of Concept (PoC)
