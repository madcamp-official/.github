<p align="center">
  <img src="../assets/madcamp-banner.png" alt="MadCamp Banner" width="60%" />
</p>

<div align="center">

# MadCamp · 몰입캠프

### 함께 몰입하는 즐거움, 몰입캠프

<img src="https://img.shields.io/badge/MadCamp-Since%202010-004191?style=for-the-badge"/>
<img src="https://img.shields.io/badge/KAIST-School%20of%20Computing-004191?style=for-the-badge"/>

**[Official Website](https://madcamp.io)** · **[Participant Guide Wiki](https://github.com/madcamp-official/participant-guide/wiki)** · **[Contact](mailto:madcamp.kaist@gmail.com)**

</div>

---

## About MadCamp

**몰입캠프(MadCamp)** 는 학생들이 자율적으로 집중 개발을 경험하는 프로그래밍 캠프입니다.

참가자들은 4주 이상 이어지는 캠프 기간 동안 팀을 이루어 서비스를 기획하고, 개발하고, 배포하며, 그 과정에서 협업과 몰입의 경험을 쌓습니다. 몰입캠프는 단순히 특정 기술을 가르치는 수업이 아니라, 다양한 학생들이 함께 개발하며 빠르게 배우고 성장하는 환경을 만드는 것을 목표로 합니다.

몰입캠프에서는 웹, 모바일, 크로스플랫폼, 게임, AI/LLM 서비스 등 다양한 형태의 프로젝트가 만들어집니다. 참가자들은 스스로 문제를 정의하고, 팀원과 역할을 나누고, 실제 사용 가능한 결과물을 완성하는 과정을 통해 개발자로서의 태도와 협업 방식을 배워갑니다.

---

## What This Organization Is For

이 GitHub Organization은 **몰입캠프의 프로젝트 산출물과 운영 자료를 체계적으로 관리하기 위한 공간**입니다.

앞으로 각 기수의 참가자 프로젝트는 이 Organization을 통해 생성, 관리, 보관됩니다. 팀별 repository에는 프로젝트 코드뿐 아니라 README, 실행 방법, 배포 링크, API 명세, DB 스키마, 회고 문서 등 주요 산출물이 함께 정리됩니다.

이 Organization의 주요 목적은 다음과 같습니다.

- 몰입캠프 참가자 프로젝트의 기수별 아카이빙
- 팀별 repository 생성 및 권한 관리
- 프로젝트 README, API 문서, DB 스키마 등 산출물 표준화
- 운영진의 GitHub Organization 운영 자동화
- 참가자들이 이후 포트폴리오와 CV에 활용할 수 있는 공개 가능한 산출물 관리
- 다음 기수 운영진과 참가자들이 참고할 수 있는 개발 기록 축적

캠프 진행 중에는 일부 repository가 private으로 운영될 수 있습니다. 공개 가능한 참가자 프로젝트는 산출물 정리와 민감 정보 제거 여부를 확인한 뒤 public archive로 관리할 수 있습니다.

---

## Project Archive

몰입캠프의 프로젝트 산출물은 단순한 과제 제출물이 아니라, 참가자들이 짧은 기간 동안 깊이 몰입하여 만들어낸 개발 경험의 기록입니다.

이 Organization은 각 기수의 산출물을 다음과 같은 방식으로 관리합니다.

| 구분 | 설명 |
|---|---|
| 기수별 관리 | 여름학기와 겨울학기 단위로 프로젝트 repository를 관리합니다. |
| 주차별 관리 | 각 주차의 팀 프로젝트를 별도 repository로 관리합니다. |
| 팀별 관리 | 한 주차의 한 팀이 하나의 repository를 사용합니다. |
| 산출물 공유 | 공개 가능한 프로젝트는 public repository로 관리하여 후속 기수와 외부에서도 참고할 수 있게 합니다. |
| 포트폴리오 활용 | 참가자는 정리된 repository를 자신의 CV, 포트폴리오, GitHub profile 등에 활용할 수 있습니다. |

프로젝트 repository는 다음과 같은 이름 규칙을 따릅니다.

```text
{year}-{semester}-w{week}-c{class}-{teamNumber}
```

예시:

```text
2026-summer-w1-c1-01
2026-summer-w2-c3-07
2026-summer-w3-c4-05
2026-summer-w4-c2-10
```

각 repository는 다음 정보를 포함하는 것을 권장합니다.

- 프로젝트 소개
- 팀원 및 역할
- 주요 기능
- 기술 스택
- 실행 방법
- 배포 링크
- 발표 자료 또는 시연 영상
- API 명세
- DB 스키마
- 회고

---

## Repository Structure

이 Organization은 다음과 같은 repository들을 중심으로 운영됩니다.

| Repository | Visibility | Purpose |
|---|---|---|
| `project-template` | Public | 참가자 프로젝트 repository 생성을 위한 기본 템플릿 |
| `participant-guide` | Public | 참가자를 위한 GitHub 사용법, 제출 규칙, 보안 가이드 |
| 운영진 관리 repository | Private | GitHub Organization 운영 매뉴얼, 자동화 스크립트, 내부 운영 자료 |
| `2026-summer-w1-c1-01` 등 | Public 또는 Private | 기수·주차·분반·팀별 프로젝트 산출물 |

---

## 2026 Summer

**2026 여름학기 몰입캠프**는 이 Organization을 기반으로 프로젝트 산출물을 체계적으로 관리하는 첫 기수입니다.

| 항목 | 내용 |
|---|---|
| 기수 | 2026 여름학기 |
| 캠프 기간 | 2026.07.02 ~ 2026.08.02 |
| 모집 인원 | 80명 이내 |
| 분반 | 4개 분반 |
| 장소 | KAIST 대전 본원 |
| 운영 방식 | 주차별 팀 프로젝트 및 산출물 아카이빙 |

### Staff

2026 여름학기 몰입캠프 운영진은 다음과 같습니다.

| 이름 | 역할 |
|---|---|
| 주영준 | 총괄 |
| 박지민 | 기술지원부 |
| 라태형 | 대외협력부 |
| 송재훈 | 재정관리부 |
| 강우현 | 참가관리부 |

---

## For Participants

> 참가자용 GitHub 사용법, 권한 안내, 제출 규칙, 배포/시연 링크 정리 방법은  
> [몰입캠프 참가자 가이드 Wiki](https://github.com/madcamp-official/participant-guide/wiki)에서 확인할 수 있습니다.

참가자는 각 주차별 팀 repository에서 프로젝트를 진행합니다.

기본적인 제출 기준은 다음과 같습니다.

- 프로젝트 코드는 배정된 팀 repository에 push합니다.
- 최종 제출 기준 branch는 `main`입니다.
- README에 프로젝트 소개, 팀원, 실행 방법, 배포 링크를 작성합니다.
- 필요한 경우 `docs/`에 기획서, API 명세, DB 스키마, 배포 문서, 회고를 작성합니다.
- `.env`, API key, DB password, token 등 민감 정보는 commit하지 않습니다.
- 실제 환경변수 값은 올리지 않고, 필요한 변수 이름만 `.env.example`에 작성합니다.
- 대용량 파일, 빌드 파일, 시연 영상 등은 외부 링크나 Release 형태로 정리합니다.

자세한 안내는 아래 문서를 참고해 주세요.

- [몰입캠프 참가자 가이드 Wiki](https://github.com/madcamp-official/participant-guide/wiki)
- [participant-guide repository](https://github.com/madcamp-official/participant-guide)

---

## Participant Guide

참가자용 Wiki에는 다음 내용이 정리되어 있습니다.

| 문서 | 내용 |
|---|---|
| [GitHub 계정 준비](https://github.com/madcamp-official/participant-guide/wiki/GitHub-%EA%B3%84%EC%A0%95-%EC%A4%80%EB%B9%84) | GitHub 계정 생성, username 확인, Git 설치 확인 |
| [Organization 참여하기](https://github.com/madcamp-official/participant-guide/wiki/Organization-%EC%B0%B8%EC%97%AC%ED%95%98%EA%B8%B0) | GitHub username 제출, Organization 초대 수락, 팀 repository 접근 확인 |
| [권한 안내](https://github.com/madcamp-official/participant-guide/wiki/%EA%B6%8C%ED%95%9C-%EC%95%88%EB%82%B4) | 참가자 권한, repository 생성/삭제 제한, GitHub App, OAuth, Actions, 배포 서비스 권한 안내 |
| [Repository 사용 규칙](https://github.com/madcamp-official/participant-guide/wiki/Repository-%EC%82%AC%EC%9A%A9-%EA%B7%9C%EC%B9%99) | 팀 repository 사용 방식, naming rule, README 작성 기준 |
| [프로젝트 유형별 제출 가이드](https://github.com/madcamp-official/participant-guide/wiki/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%9C%A0%ED%98%95%EB%B3%84-%EC%A0%9C%EC%B6%9C-%EA%B0%80%EC%9D%B4%EB%93%9C) | Web, Mobile, Game, AI/LLM 등 프로젝트 유형별 repository 정리 방법 |
| [환경변수와 보안](https://github.com/madcamp-official/participant-guide/wiki/%ED%99%98%EA%B2%BD%EB%B3%80%EC%88%98%EC%99%80-%EB%B3%B4%EC%95%88) | public repository 사용 시 `.env`, API key, secret 관리 주의사항 |
| [대용량 파일과 Git LFS](https://github.com/madcamp-official/participant-guide/wiki/%EB%8C%80%EC%9A%A9%EB%9F%89-%ED%8C%8C%EC%9D%BC%EA%B3%BC-Git-LFS) | Git LFS 미지원 안내, 대용량 파일과 빌드 파일 제출 방식 |
| [배포와 시연 링크](https://github.com/madcamp-official/participant-guide/wiki/%EB%B0%B0%ED%8F%AC%EC%99%80-%EC%8B%9C%EC%97%B0-%EB%A7%81%ED%81%AC) | 배포 링크, API 문서, 앱 패키지, 게임 빌드, 시연 영상 정리 방법 |
| [최종 제출 체크리스트](https://github.com/madcamp-official/participant-guide/wiki/%EC%B5%9C%EC%A2%85-%EC%A0%9C%EC%B6%9C-%EC%B2%B4%ED%81%AC%EB%A6%AC%EC%8A%A4%ED%8A%B8) | 마감 전 확인해야 할 최종 점검 항목 |

---

## For Staff

운영진은 이 Organization을 통해 참가자 프로젝트 repository를 생성하고, 팀별 권한을 관리하며, 각 기수의 산출물을 정리합니다.

운영진이 관리하는 주요 항목은 다음과 같습니다.

- 참가자 GitHub username 수집
- 주차별 팀 편성 CSV 관리
- repository 및 GitHub Team 자동 생성
- 팀별 repository 권한 부여
- `project-template` 유지보수
- 캠프 종료 후 공개 가능한 repository 정리
- 다음 기수를 위한 운영 매뉴얼 개선

세부 운영 방식은 내부 운영 문서와 자동화 repository에서 관리합니다.

---

## History

몰입캠프는 2010년 본엔젤스의 매드캠프에서 시작되었습니다.

MadCamp는 원래 **Mobile Application Development Camp**의 약자로, 모바일 앱 개발에 관심 있는 학생들이 함께 모여 프로젝트를 진행하며 빠르게 성장하는 합숙형 프로그래밍 캠프였습니다. 2010년 겨울학기 1기 모집을 시작으로 운영 경험과 노하우를 쌓아왔고, 2015년 겨울학기부터는 KAIST 전산학부와 함께 몰입캠프로 이어져 왔습니다.

2017년 겨울학기부터는 국내 타 대학으로 모집 범위를 넓혔고, 이후 다양한 대학의 학생들이 함께 참여하는 개발 캠프로 발전했습니다.

2023년 여름학기부터는 이전 몰입캠프에 참가했던 KAIST 학생들이 운영의 주체가 되어, 캠프의 정신을 이어받아 직접 기획하고 운영하고 있습니다.

---

## Milestones

| Year | Semester | Notes |
|---|---|---|
| 2010–2014 | - | 본엔젤스 매드캠프 1기 ~ 9기 운영 |
| 2015 | Winter | KAIST 전산학부와 함께 몰입캠프 1기 시작 |
| 2017 | Winter | 국내 타 대학 모집 시작 |
| 2023 | Summer | KAIST 학생 운영진 중심 운영 시작 |
| 2025 | Summer | 몰입캠프 19기, 참가생 80명 |
| 2025 | Winter | 몰입캠프 20기, 참가생 78명 |
| 2026 | Summer | GitHub Organization 기반 산출물 아카이빙 체계 도입 |

---

## Contact

문의사항은 아래 이메일로 연락해 주세요.

**madcamp.kaist@gmail.com**

공식 웹사이트는 아래에서 확인할 수 있습니다.

**https://madcamp.io**

---

<div align="center">

**MadCamp · 몰입캠프 Since 2010**

함께 몰입하는 즐거움, 몰입캠프

</div>
