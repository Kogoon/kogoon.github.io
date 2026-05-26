---
title: About
permalink: /about/
layout: page
excerpt: 클라우드 엔지니어 & 보안담당자 Kogoon의 소개 페이지
comments: false
---

안녕하세요.  
현재 케어랩스에서 클라우드 엔지니어이자 보안담당자로 일하고 있습니다.  
다양한 산업군의 AWS 아키텍처 설계 및 구축 경험을 바탕으로, 현 회사의 클라우드 인프라와 보안 체계를 고도화해 나가고 있습니다.  
이 블로그에는 그 과정에서 경험하고 배운 지식을 기록하고 공유합니다.

---

### 💼 Experience

<style>
  .timeline-container {
    position: relative;
    max-width: 800px;
    margin: 2.5rem 0;
    padding-left: 2rem;
  }
  
  /* Vertical Timeline Line */
  .timeline-container::before {
    content: '';
    position: absolute;
    top: 0.5rem;
    bottom: 0.5rem;
    left: 7px;
    width: 2px;
    background: rgba(128, 128, 128, 0.2);
    border-radius: 1px;
  }

  .timeline-item {
    position: relative;
    margin-bottom: 3rem;
  }

  .timeline-item:last-child {
    margin-bottom: 1rem;
  }

  /* Timeline Dot - Light Mode (Warm Bronze / Brown) */
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -29px;
    top: 6px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: #8a5a36; /* Warm amber brown */
    border: 3px solid #fff;
    z-index: 1;
    transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
  }
  
  .timeline-item:hover::before {
    transform: scale(1.4);
    background: #a06a3f;
    box-shadow: 0 0 8px rgba(160, 106, 63, 0.4);
  }

  .timeline-date {
    font-size: 0.8rem;
    font-weight: 700;
    color: #7f8c8d;
    margin-bottom: 0.35rem;
    letter-spacing: 1px;
  }

  .timeline-title {
    font-size: 1.2rem;
    font-weight: 700;
    margin: 0 !important;
    color: #2c3e50;
  }

  .timeline-company {
    font-size: 0.95rem;
    font-weight: 600;
    color: #8a5a36; /* Matches the dot color */
    margin-bottom: 0.75rem;
    display: inline-block;
  }

  .timeline-desc {
    font-size: 0.95rem;
    line-height: 1.6;
    color: #34495e;
  }
  
  .timeline-desc p {
    margin: 0 0 0.5rem 0 !important;
  }
  
  .timeline-desc ul {
    margin: 0.5rem 0 0 1.2rem !important;
    list-style-type: disc;
  }

  .timeline-desc li {
    margin-bottom: 0.35rem;
  }
  
  .project-title {
    font-weight: 700;
    margin-top: 0.8rem;
    color: #2c3e50;
  }
  
  .project-desc-list {
    margin-top: 0.2rem !important;
    margin-bottom: 0.8rem !important;
    font-size: 0.9rem;
    color: #555;
  }

  /* Dark Mode Styling overrides (Adapts to Klise Dark Colors) */
  body[data-theme="dark"] .timeline-container::before {
    background: rgba(255, 255, 255, 0.15);
  }
  
  body[data-theme="dark"] .timeline-item::before {
    background: #c08552; /* Soft warm copper / light brown */
    border-color: #131418; /* Fits $dark-black background */
  }
  
  body[data-theme="dark"] .timeline-item:hover::before {
    background: #d39e7c; /* Bright copper highlight */
    box-shadow: 0 0 8px rgba(211, 158, 124, 0.5);
  }
  
  body[data-theme="dark"] .timeline-date {
    color: #95a5a6;
  }
  
  body[data-theme="dark"] .timeline-title {
    color: #ecf0f1;
  }
  
  body[data-theme="dark"] .timeline-company {
    color: #c08552;
  }
  
  body[data-theme="dark"] .timeline-desc {
    color: #bdc3c7;
  }
  
  body[data-theme="dark"] .project-title {
    color: #ecf0f1;
  }
  
  body[data-theme="dark"] .project-desc-list {
    color: #a5b1b2;
  }
</style>

<div class="timeline-container">
  
  <div class="timeline-item">
    <div class="timeline-date">2025.08 - PRESENT</div>
    <h4 class="timeline-title">클라우드 엔지니어 & 보안담당자</h4>
    <div class="timeline-company">(주)케어랩스 Carelabs</div>
    <div class="timeline-desc">
      <p>사내 서비스 인프라의 안정적인 클라우드 운영 및 전사적 정보보호 체계 강화를 위한 업무를 수행하고 있습니다.</p>
      <ul>
        <li>ISMS 등 국내 정보보호 컴플라이언스 인증 획득 및 유지를 위한 기술적 보호조치 수립 및 관리</li>
        <li>Amazon OpenSearch Service 기반의 중앙 집중형 SIEM 구축을 통한 보안 위협 모니터링 및 침해 탐지 고도화</li>
        <li>차세대 방화벽(Fortigate) 및 호스트 보안 솔루션(Deep Security) 운영 및 고도화</li>
        <li>클라우드 접근 통제(IAM Identity Center) 체계 고도화 및 보안 아키텍처 설계 및 구축</li>
        <li>클라우드 인프라(AWS/IDC 등) 아키텍처 설계, 운영 및 비용 최적화</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2022.12 - 2025.08</div>
    <h4 class="timeline-title">AWS Solutions Architect (Security)</h4>
    <div class="timeline-company">MegazoneCloud</div>
    <div class="timeline-desc">
      <p>AWS 환경에서의 클라우드 보안 아키텍처 수립 및 고객사 보안 강화를 위한 전문 컨설팅을 수행했습니다.</p>
      
      <div class="project-title">주요 수행 프로젝트:</div>
      <ul>
        <li>
          <strong>이커머스 플랫폼 Control Tower 기반 Landing Zone 설계 및 구축 (Security SA)</strong>
          <ul class="project-desc-list">
            <li>AWS Control Tower 기반 Landing Zone 구축으로 Cross Account 환경의 보안 및 거버넌스 체계 수립 지원</li>
            <li>AWS 네이티브 보안 서비스를 활용한 클라우드 종합 보안 아키텍처 설계 및 구축, Logging/Backup/Monitoring 가이드 제공</li>
          </ul>
        </li>
        <li>
          <strong>핀테크 서비스 전자금융업 인허가를 위한 보안 인프라 구축 (SA)</strong>
          <ul class="project-desc-list">
            <li>IaC(Terraform)를 활용한 전자금융업 인허가 요건 만족용 Multi Account AWS 보안 인프라 설계 및 구축</li>
            <li>Assume Role 기반 최소 권한 접근 제어 정책 구현, Logging, Backup 중앙화 구성, OS 취약점 조치</li>
          </ul>
        </li>
        <li>
          <strong>게임 플랫폼 Multi CDN 솔루션 운영 및 보안 관리 (SA)</strong>
          <ul class="project-desc-list">
            <li>데이터 관리를 위한 AWS IAM 및 S3 버킷 정책 관리, AWS WAF 서비스를 통한 IP 기반 접근제어 지원</li>
            <li>CloudFront 환경 구성 및 S3 Lifecycle 등의 비용 최적화 아키텍처 구성 지원</li>
          </ul>
        </li>
        <li>
          <strong>F&B 프랜차이즈 앱 현대화 및 AWS 리아키텍팅 (SA)</strong>
          <ul class="project-desc-list">
            <li>모놀리식 애플리케이션의 Docker 기반 컨테이너화 및 Amazon ECS 서비스 구조 설계 및 배포</li>
            <li>GitHub, Jenkins, AWS CodePipeline을 활용한 CI/CD 파이프라인 구축 및 Cross Account 기반 보안/운영 분리</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
  
</div>

---

### 🛠️ Core Skills

*   **Cloud Security**: AWS Control Tower (Landing Zone), IAM / Identity Center, AWS WAF & Shield, Encryption (KMS / Secrets Manager), SIEM (Amazon OpenSearch)
*   **DevSecOps & CI/CD**: CodePipeline, HashiCorp Terraform, CloudFormation
*   **Compliance**: ISMS, AWS Well-Architected Framework (Security Pillar)
*   **Infrastructure**: Windows & Linux Administration, Network & Security, Container Orchestration (Docker, Amazon ECS & EKS)

---

### 📞 Contact & Channel

제게 궁금한 점이 있으시거나 글 관련 문의는 아래 채널을 통해 연락 주시면 성실히 답변해 드리겠습니다.

- 📧 Email: [{{ site.author.email }}](mailto:{{ site.author.email }})
- 🐙 GitHub: [github.com/{{ site.author.github }}](https://github.com/{{ site.author.github }})
- 💬 Issue Report: [Feedback / Report Bug](http://github.com/kogoon/kogoon.github.io/issues/new)
