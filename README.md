# starbucks_store

스파로스 아카데미 6기 스타벅스 온라인 스토어 클론 코딩 프로젝트

## 목차
1. [기획](#1-기획-의도-및-기대-효과)
2. [개발 환경](#2-개발-환경)
3. [주요 기능](#3-주요-기능)
4. [기술 소개](#4-기술-소개)
5. [설계 문서](#5-설계-문서)
6. [팀원 소개](#6-팀원-소개)
7. [프로젝트 규칙](#7-프로젝트-규칙)
8. [포팅 메뉴얼](#8-포팅-메뉴얼)

## 1. 기획

---

## 2. 개발 환경
### Frontend
| Name | Version |
| --- | --- |
| Next.js | - |
| Typescript | - |
| - | - |
| - | - |
| - | - |
| -| - |

### Backend
| Name | Version |
| --- | --- |
| - | - |
| - | - |
| - | - |
| - | - |
| - | - |
| -| - |

### Infra
| Name | Version |
| --- | --- |
| - | - |
| - | - |
| - | - |
| - | - |
| - | - |
| -| - |

### CI/CD
| Name | Version |
| --- | --- |
| - | - |
| - | - |

---

## 3. 주요 기능

---

## 4. 기술 소개

---

## 5. 설계 문서

### 와이어 프레임 Web

> 추가 예정

### 시스템 아키텍쳐

> 추가 예정

### ERD

> 추가 예정

### 요구사항 정의서

> 추가 예정

### API명세서

> 추가 예정

---

## 6. 팀원 소개

|  |  |  |  |  |  |
|:---:|:---:|:---:|:---:|:---:|:---:|
|  |  |  |  |  |  |
| Backend |  |  | Infra/Backend | Frontend |  |

**Backend**

**Frontend**

**Infra**

---

## 7. 프로젝트 규칙

### 1. 커밋 메시지 구조
커밋 메시지는 제목, 본문, 그리고 꼬리말로 구성됩니다.
[<스코프>]<타입>: <제목>

<본문>

<꼬리말>

#### *스코프(Scope)*
변경 사항의 범위를 나타냅니다. 예를 들어, 특정 모듈이나 기능의 이름을 사용할 수 있습니다.
- 예: auth, payment, ui, backend
#### *타입(Type)*
타입의 첫글자는 대문자로 작성합니다.
- *feat*: 새로운 기능 추가
- *fix*: 버그 수정
- *docs*: 문서 변경
- *style*: 코드 포맷팅, 세미콜론 누락 등 비즈니스 로직에 영향을 주지 않는 변경
- *remove*: 파일 삭제
- *refactor*: 코드 리팩토링, 기능 변경 없이 코드 개선
- *test*: 테스트 추가, 수정
- *chore*: 빌드 과정 또는 보조 도구 수정, 패키지 매니저 설정 등
- *perf*: 성능 향상 관련 변경
- *ci*: CI 구성 파일 및 스크립트 변경
- *wip*: 작업 진행 중 임시 저장
#### *제목(Subject)*
제목은 변경 사항을 간략하게 설명합니다. 첫 글자는 대문자로 작성하고, 명령문 형식으로 작성합니다.
- 50자를 넘지 않도록 하며, 마지막에 마침표를 찍지 않습니다.
- 예: [auth]feat: Add JWT authentication
#### *본문(Body)*
본문은 변경 사항의 이유와 주요 내용을 설명합니다. 필요 시 다음과 같은 규칙을 따릅니다:
- 한 줄에 72자를 넘지 않도록 합니다.
- "어떻게" 보다는 "무엇을", "왜" 변경했는지 설명합니다.
- 예:
    - Add JWT authentication to secure API endpoints
    - Update login method to issue JWT tokens
    - Modify user model to store JWT refresh tokens
    
    
---
### 2. Git 브랜치 작성 컨벤션

#### *브랜치 타입*
브랜치 타입을 명확히 구분하여 브랜치 이름을 작성합니다:
- *feature*: 새로운 기능 개발
- *bugfix*: 버그 수정
- *hotfix*: 긴급 수정
- *release*: 릴리스 준비
- *refactor*: 코드 리팩토링
- *test*: 테스트 관련 작업
- *chore*: 기타 잡무
- *wip*: 작업 진행 중 임시 저장
#### *브랜치 네이밍 규칙*
브랜치 이름은 <타입>/<설명> 형식을 따릅니다. 이슈 번호는 관련된 이슈 트래커의 번호를 사용하고, 설명은 변경 사항을 간략하게 나타냅니다.
- *feature* 브랜치: 새로운 기능 추가
    - 예: feature/login-main
    - feature의 main branch는 -main을 작성합니다.
    - feature의 하위 branch는 다음과 같이 작성합니다. (feature/login/create)
- *bugfix* 브랜치: 버그 수정
    - 예: bugfix/fix-login-error
- *hotfix* 브랜치: 긴급 수정
    - 예: hotfix/critical-bug-fix
- *release* 브랜치: 릴리스 준비
    - 예: release/1.0.0
- *refactor* 브랜치: 코드 리팩토링
    - 예: refactor/optimize-auth-module
- *test* 브랜치: 테스트 관련 작업
    - 예: test/add-unit-tests
- *chore* 브랜치: 기타 잡무
    - 예: chore/update-dependencies
---
### 3. 브랜치 관리
- *main*: 항상 배포 가능한 상태를 유지합니다.
- *develop*: 다음 릴리스에 포함될 기능이 합쳐지는 브랜치입니다.

---

## 8. 포팅 메뉴얼

이 프로젝트는 [Next.js](https://nextjs.org) 프로젝트입니다.

### Getting Started

먼저, 개발 서버를 실행합니다:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

브라우저에서 [http://localhost:3000](http://localhost:3000) 을 열어 결과를 확인하세요.

페이지는 app/page.tsx 파일을 수정하여 편집을 시작할 수 있습니다. 파일을 수정하면 페이지가 자동으로 업데이트됩니다.

이 프로젝트는 [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) 를 사용하여 [Geist](https://vercel.com/font)라는 새로운 글꼴을 자동으로 최적화하고 로드합니다.

## Learn More

Next.js에 대해 더 알아보려면 다음 리소스를 참고하세요:

- [Next.js Documentation](https://nextjs.org/docs) - Next.js 기능 및 API에 대해 배우기
- [Learn Next.js](https://nextjs.org/learn) - 대화형 Next.js 튜토리얼

[the Next.js GitHub repository](https://github.com/vercel/next.js)도 확인해보세요. 여러분의 피드백과 기여를 환영합니다!
