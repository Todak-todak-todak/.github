# 국내 및 외국인 노동자를 위한 통합형 산재 대응 플랫폼 Todak
<a href="https://todak-ten.vercel.app/" target="_blank">
<img src="https://github.com/user-attachments/assets/8b91b4fc-80e6-4118-ad90-150ac649eca3" alt="배너" width="100%"/>
</a>

<br/>
<br/>

# 0. Getting Started (시작하기)

[서비스 링크](https://todak-ten.vercel.app/)

<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
Todak은 국내 근로자 뿐만 아니라 외국인 노동자의 산재 피해 대응부터 예방, 의료기관 연계, 요양급여 신청 지원까지 전 과정을 다국어로 지원하는 AI 기반 챗봇 서비스이다. 해당 시스템은 웹앱 형태로 구현되어 있으며, 사용자 인터페이스에서 자연어로 질문을 입력하면 GPT 기반 AI가 유사 판례를 검색하고, 산재 인정 가능성과 데이터에 기반한 유사 사례를 안내한다. 

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| 김성헌 | 강재준 | 이나경 | 진채정 |
|:------:|:------:|:------:|:------:|
| <img src="https://github.com/user-attachments/assets/e084c2ff-1b31-4cf6-8a4b-f8b3c09a9639" alt="김성헌" width="150"> | <img src="https://github.com/user-attachments/assets/78ec4937-81bb-4637-975d-631eb3c4601e" alt="강재준" width="150"> | <img src="https://github.com/user-attachments/assets/13e37ba9-06b3-42c4-9b13-8fb482680fb6" alt="이나경" width="150"> | <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="진채정" width="150"> |
| BE | AI | FE | FE |
| [GitHub](https://github.com/sungheonkim) | [GitHub](https://github.com/orgs/Todak-todak-todak/people/BBZJUN) | [GitHub](https://github.com/lee-nakyung) | [GitHub](https://github.com/ahcgnoej) |

<br/>
<br/>

# 3. Development Period(개발 기간)

2025.03.15 ~ 2025.03.22

- 아이디어 회의
- 개발 기획
- UI 설계

2025.03.23 ~ 2025.04.05

- 시스템 아키텍처 설계
- 데이터베이스 스키마 설계
- UI 설계 및 수정
- 기능 명세서 작성
- API 명세서 작성

2025.04.06 ~ 2025.05.05

- 백엔드,프론트엔드,AI 개발
- API 연동 및 디버깅
- CI/CD 설정 및 배포

2024.05.06 ~ 2024.05.14

- 사업계획서 작성
- 고용노동부 공공데이터 공모전 제출

# 4. Technology Stack (기술 스택)

- Front End : React, TypeScript, TailwindCSS, Tanstack-Query, Zustand, React-Hook-Form, Zod
- Back End : Java17, Spring boot(3.4.3), Spring Security, Spring JPA, JWT,OAuth2, MYSQL, Gradle, JUnit5
- AI :
- 형상 관리 : GitHub, Jira
- 협업 툴 : Notion, Discord
- CI/CD : GitHun Actions
- 배포 : AWS EC2, Vercel
- UI/UX : Figma

# 4. Collaboration Process (협업 과정)

**🤝 협업 과정**
- 스크럼 방법론 기반 2주 스프린트 단위 개발, 데일리 스크럼 및 스프린트 리뷰/회고 진행

**🌿 브랜치 전략**
- `main`: 프로덕션 배포 브랜치
- `dev`: 개발 통합 브랜치  
- `feature`: 기능별 개발 브랜치

**🗒️ 커밋 컨벤션**

| Gitmoji Code | Gitmoji | 설명 |
| --- | --- | --- |
| `:tada:` | 🎉 | Init: 최초 파일 생성 |
| `:sparkles:` | ✨ | Feat: 기능 구현 첫 커밋 할 때 |
| `:pencil2:` | ✏️ | Fix: 자잘한 코드 수정 |
| `:art:` | 🎨 | Refactor: 코드 수정 (기능 수정 없이 이쁘게 최적화) |
| `:ambulance:` | 🚑 | Hotfix: 급하게 치명적인 버그를 고쳐야하는 경우 |
| `:rewind:` | ⏪️ | Revert: 변경 사항 되돌리기 |
| **`:memo:`** | 🗒️ | Docs: 문서 수정 (문서 추가, 수정, 삭제, README) |
| `:wrench:` | 🔧 | Chore: 기타 변경사항 (빌드 스크립트 수정, assets, 패키지 매니저 등) |
| `:label:` | 🏷️ | Rename: 파일 혹은 폴더명을 수정하거나 옮기는 작업만 한 경우 |
| `:coffin:` | ⚰️ | Remove: 파일을 삭제하는 작업만 수행한 경우 |

**💬 이슈 컨벤션**

| 함목 | 설명 |
| --- | --- |
| `Summary` | 작업 요약 |
| `Braach Name` | feature/{작업설명}, fix/{버그설명} |
| `Due Date` | YYYY/MM/DD |
| `References` | 관련 자료 링크 |
| `Checklist` | 할 일 리스트 |

**🗒️ PR Template**

```markdown
## ✨ 변경 사항

- 어떤 UI/기능을 수정 또는 추가했는지 간단히 요약해주세요.
- 예: 헤더 컴포넌트 반응형 개선, 로그인 폼 유효성 추가 등
S
## ✅ 작업 내용 상세

- [ ] 주요 기능 1 (설명)
- [ ] 주요 기능 2 (설명)
- (선택) 관련 이슈: #이슈번호

## 🖼️ 스크린샷 (선택)

- 시각적 변화가 있는 경우 첨부해주세요!
- ex: Before / After 비교

## 🙏 리뷰 포인트

- 리뷰 시 중점적으로 봐줬으면 하는 부분이 있다면 작성해주세요.
- 예: 스타일 구조, 컴포넌트 분리, 로직 가독성 등

```

# 5. Database ERD

![Image](https://github.com/user-attachments/assets/506764a6-0d0b-42c7-b025-0f36bd29fc22)

# 6. Architecture Diagram

![Image](https://github.com/user-attachments/assets/b501b47f-d96f-4a57-9adb-f8899003dfbf)

# 7. Service Function(서비스 기능)

- **회원가입**:
  <img width="1100" alt="Image" src="https://github.com/user-attachments/assets/ef2fa9fd-848c-41fa-b37c-f6f42cba3038" />
  - 카카오 소셜 로그인 
  - 언어 선택으로 다국어 지원
  - 추가 정보 기입 후 최종 회원가입

- **홈 화면**:
  <img width="1100" alt="Image" src="https://github.com/user-attachments/assets/4d4d0302-a698-4cce-922d-f0ef4ed06c82" />
  <img width="1100" alt="Image" src="https://github.com/user-attachments/assets/64717268-0d48-4a33-a603-125e70f8be0d" />
  - 종사하는 산업군에 대한 주의사항, 안전교육, 의료기관, 상담, 신고 정보 제공
  - 종사하는 산업군에서 가장 많이 발생하는 사고유발 원인, 부상 TOP3를 시각적인 도표로 제공 

- **산재 챗봇**:
  <img width="1101" alt="Image" src="https://github.com/user-attachments/assets/e715ff6c-00d9-4b46-a75f-bbb3fa87b850" />
  - 사용자의 산재 처리 여부 질문을 처리하는 챗봇AI
  - 사용자의 상황 요약과 산재 인정 확률 제공
  - 사용자의 상황과 비슷한 사례 제공
  - 공통적인 질문에 대한 정보 제공

- **분석 결과**:
  <img width="1102" alt="Image" src="https://github.com/user-attachments/assets/784834cd-1b1d-41fd-8a27-2cda302e5a29" />   
  - 산재 처리 가능성 확률 제공 및 산재 신청 서류 작성으로 이동하는 버튼
  - 사용자 위치 기반 인근 산재 지정 병원 안내(카카오 Map 활용하여 시작적인 정보 제공)
  - 유형별 산재 보험 계산기 제공
  - 같은 산업군의 비슷한 사례 정보 제공

- **전자 산재 신청**:
  <img width="1104" alt="Image" src="https://github.com/user-attachments/assets/3ee741d7-a8d0-47a8-bc8e-26d8b2d13f3f" />
  <img width="1099" alt="Image" src="https://github.com/user-attachments/assets/cb531ec2-63ec-4b08-827d-6ce8224e37a6" />
  - 개인정보 수집, 제공과 대리인 제공 동의
  - 산재 신청에 필요한 정보 입력
  - 산재 신청 목록 및 처리 여부 제공

- **내 정보**:
  - 개인정보 수정 가능
  - 로그아웃 제공

<br/>
<br/>



