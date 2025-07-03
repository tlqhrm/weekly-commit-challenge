# 위클리 커밋 챌린지

<div align="center">

![Weekly Commit Challenge](./docs/images/og.png)

**GitHub 개발자를 위한 꾸준한 커밋 도전**

**생각보다 쉽지 않을 걸요? 매주 커밋할 자신 있나요?**

[![Fork Repository](https://img.shields.io/badge/Fork_Repository-brightgreen?style=for-the-badge&logo=github)](https://github.com/tlqhrm/weekly-commit-challenge/fork)
[![Dashboard](https://img.shields.io/badge/챌린지_대시보드-blue?style=for-the-badge)](https://tlqhrm.github.io/weekly-commit-challenge/)

</div>

## 챌린지 소개

### 다양한 챌린지 타입
**TIL · 개인 프로젝트 · 오픈소스 · 알고리즘 문제 · 스터디**

**무엇이든 좋습니다! 꾸준한 성장이 목표예요!**

매시간 30분에 GitHub Actions가 자동으로 실행되어 지난 일주일간 커밋을 확인하고 기록하는 챌린지 시스템입니다.

**지금 참여하면 이번 주부터 기록이 시작됩니다**

## 실시간 통계

<div align="center">

### [챌린지 대시보드](https://tlqhrm.github.io/weekly-commit-challenge/)에서 실시간 현황을 확인하세요!

| 통계 | 설명 |
|------|------|
| **도전자** | 현재 챌린지에 참여하는 총 인원 |
| **이번 주 성공** | 이번 주 성공적으로 커밋한 도전자 수 |
| **평균 성공률** | 전체 도전자의 평균 성공률 |
| **평균 연속 성공** | 도전자들의 평균 연속 성공 주차 |

</div>

## 도전자 랭킹

4가지 카테고리별 랭킹을 확인할 수 있습니다:

- **연속 도전 중**: 현재 연속으로 성공하고 있는 주차 수
- **성공률**: 전체 참여 주차 대비 성공률  
- **최고 연속 기록**: 역대 최장 연속 성공 주차 수
- **이번 주 커밋 수**: 현재 주차의 커밋 수

## 내 참여 현황

GitHub 사용자명 또는 프로필 URL을 입력하여 개인 현황을 조회할 수 있습니다.

**예시**: `tlqhrm` 또는 `https://github.com/tlqhrm`

---

## 참여 방법

### 1. 이 레포지토리 Fork 하기

GitHub에서 이 레포지토리를 Fork하여 본인 계정으로 복사하세요.

<div align="center">

[![Fork Repository](https://img.shields.io/badge/Fork_Repository-brightgreen?style=for-the-badge&logo=github)](https://github.com/tlqhrm/weekly-commit-challenge/fork)

</div>

### 2. GitHub Actions 활성화

Fork한 레포지토리의 Actions 탭에서 워크플로우를 활성화하세요.

**Repository → Actions → "I understand my workflows, go ahead and enable them"**

#### 워크플로우 활성화 가이드

<details>
<summary><strong>단계별 가이드 보기</strong></summary>

#### **1단계: Actions 활성화 허용**
![GitHub Actions 활성화 허용](./docs/images/allow-action.png)

"I understand my workflows, go ahead and enable them" 버튼을 클릭하여 Actions를 허용하세요.

#### **2단계: 워크플로우 활성화**  
![워크플로우 활성화 버튼 클릭](./docs/images/enable-action.png)

"Weekly Commit Tracker" 워크플로우의 "Enable workflow" 버튼을 클릭하여 활성화하세요.

#### **3단계: 수동 실행 (선택사항)**
즉시 기록을 시작하려면 "Run workflow" 버튼을 클릭하여 수동으로 실행하세요.

</details>

### 3. 일주일에 한 번 커밋하기!

매시간 30분에 자동으로 실행되어 지난 일주일간의 커밋을 체크하고 기록합니다.

**일주일에 한 번만 커밋해도 성공 기록!**  
**record.md에 참여 내역이 테이블로 누적됩니다**

#### 동기부여 메시지

> "매주 한 번쯤은 커밋할 수 있지 뭐" 라고 생각하시나요?  
> 실제로는 2주만 지나도 깜빡하기 쉬워요!  
> 진짜 개발자라면 꾸준함을 증명해보세요!

#### 참여 기록 예시

| ID | 기간 | 주차 | 커밋 수 | 성공 여부 |
|---|---|---|---|---|
| 1 | 06/23 ~ 06/29 | 2025년 25주차 | 5 | ✅ 성공 |
| 2 | 06/30 ~ 07/06 | 2025년 26주차 | 3 | ✅ 성공 |
| 3 | 07/07 ~ 07/13 | 2025년 27주차 | 0 | ❌ 실패 |

---

## 워크플로우 작동 방식

### 1. 실행 주기
**매시간 30분** 자동 실행  
수동 실행 가능: GitHub Actions → "Run workflow"

### 2. Fork 사용자 초기화
Fork 후 첫 실행시 **자동으로 개인 기록 초기화**

- 원본 사용자 데이터가 자동으로 삭제됨
- 깨끗한 새 테이블로 시작

### 3. 커밋 집계 및 기록

본인 계정의 **공개 레포지토리만** 수집

#### 집계 규칙

| 포함 | 제외 |
|------|------|
| 본인 계정의 공개 레포지토리 | weekly-commit-challenge 레포지토리 |
| | 봇이 작성한 커밋 (dependabot, renovate 등) |

#### 집계 기간
- 현재 주차 월요일 00:00 ~ 일요일 23:59
- 목요일 실행 시에도 이번 주 전체 기간 조회

---

## README에 카드 추가하기

### 1. 코드 복사하기

GitHub 프로필 README에 실시간으로 업데이트되는 카드를 추가해보세요

```markdown
<a href="https://tlqhrm.github.io/weekly-commit-challenge/">
  <img src="https://weekly-commit-card.wjstls123.workers.dev/?username=YOUR_USERNAME" alt="Weekly Commit Challenge" />
</a>
```

`YOUR_USERNAME`을 본인의 GitHub 사용자명으로 변경하세요

### 2. 결과 확인

README에 추가하면 다음과 같은 카드가 표시됩니다

<div align="center">

<a href="https://tlqhrm.github.io/weekly-commit-challenge/">
  <img src="https://weekly-commit-card.wjstls123.workers.dev/?username=tlqhrm" alt="Weekly Commit Challenge Card Example" />
</a>

</div>

---

## 주의사항

### Organization 계정 사용 불가
Organization 계정으로는 Weekly Commit Challenge에 참여할 수 없습니다. 반드시 개인 사용자 계정으로 Fork해주세요.

### Sync Fork 주의
"Sync fork"를 실행하면 모든 기존 기록이 삭제됩니다. 기록을 보존하려면 sync를 하지 마세요.

### 챌린지 중단하기
챌린지를 그만두려면 Fork한 레포지토리를 삭제하면 됩니다.

### 일요일 늦은 시간 커밋 주의
일요일 23:30 ~ 23:59 사이의 커밋은 누락될 수 있습니다. 해당 시간에 커밋을 하셨다면 수동으로 워크플로우를 실행해 주세요.

### 처음부터 다시 시작하기
처음부터 다시 시작하려면 레포지토리를 삭제 후 다시 Fork하면 됩니다.

---

<div align="center">

## 지금 바로 시작하세요!

[![Fork Repository](https://img.shields.io/badge/Fork_Repository-brightgreen?style=for-the-badge&logo=github)](https://github.com/tlqhrm/weekly-commit-challenge/fork)

**© 2025 위클리 커밋 챌린지 by [tlqhrm](https://github.com/tlqhrm)**

*GitHub 개발자를 위한 꾸준한 커밋 습관 만들기 프로젝트*

</div>
