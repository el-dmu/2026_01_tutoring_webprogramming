# 🚀 웹프로그래밍기초 튜터링 (EL)

이 저장소는 **2026년 웹 프로그래밍 튜터링** 학습 과정과 과제물을 관리하는 공간입니다.

---
## 📁 폴더 구조

모든 작업물은 본인의 이름 폴더 하위에 주차별로 정리합니다.

- **규칙**: `[본인이름] / [주차폴더] / [프로젝트]`
- **예시**: 

```text
├── chaerin
│   └── week00
│       └── Hello.html
├── ...
└── README.md (전체 가이드)
```
---
## 🌿 브랜치 규칙
브랜치는 매주 학습 내용에 맞춰 아래 형식으로 생성합니다.

- **브랜치 명**: `이름(영어로)_week00`

  - (**ex**: `chaerin_week00`)

---
## 🔀 Pull Request 규칙
과제 제출 및 코드 리뷰를 위해 PR을 생성할 때 아래 규칙을 준수합니다.
- PR 제목: `[week00] 이름 N주차 실습`
  - (ex : `[week00] 이채린 0주차 실습`)
- PR 내용:
  - 실습하며 느낀점
  - 새롭게 알게 된 점 혹은 기술적 고민
  
PR 작성 이후에 우측부분에서 Reviewer 및 Assignee 지정해주세요!
<img width="712" height="419" alt="image" src="https://github.com/user-attachments/assets/a7381336-b5c5-4bb0-ae92-47c8eb3cbc59" />


### Reviewer & Assignee
- Reviewer : 튜티(Chae102)
- Assignee : 튜터 (본인)

📍 **Merge 규칙 :
PR 병합은 튜터링 진행 후, 해당 튜티가 최종 Merge (그 외 인원은 Merge 하지 않음)**

---

# 💡튜터링에서 Git 사용법

## 🛠️ 1. 기본 세팅

- Github 로그인하기 🔑
  -  https://github.com/

- Git 설치 📥
  -  https://git-scm.com/install/windows

- git 계정 정보 설정 👤
  - 폴더 생성 -> 폴더 내 우클릭 -> `Git Bash Here` 선택  
  - `git config --global user.name "사용자이름"`  
  - `git config --global user.email "이메일"`  

## 📥 2. 프로젝트 받아오기

- `git clone 주소명`
  - 주소 가져오는 법 : `2026_01_tutoring_webprogramming` 들어가기-> `Code` → `https`우측 복사 버튼
    <img width="2028" height="1080" alt="image" src="https://github.com/user-attachments/assets/1cdd2284-d710-4c68-8c11-f34db094461c" />


## 🌿 3. 작업 브랜치 생성 및 이동

- 브랜치 생성하기 ✨
  - `git branch 브랜치명`
  - 형식 : `영어이름_주차`
  - (예시 : `git branch chaerin_week00`)

- 브랜치로 이동하기 🚀
  - `git switch 브랜치명`
    
## 💻4. 실습하기
- 파일 생성 및 실습 📝
  - 본인 폴더 > 해당 주차 폴더 생성(`week00`) > 파일 생성 후 실습(`.html`)
  - (ex. `chaerin` > `week00` > `Hello.html`)

## 📤 5. 작업 내용 업로드
- 상태 확인 ✅
  - 위치 : `본인이 처음 만든 폴더` / 브랜치 : `본인이름_week00`
- 변경 사항 담기 📦
  - 'git add .` : 실습한 모든 파일 선택
- 메시지 기록 💬
  - `git commit -m "[week00] 이름 0주차 실습"`
- 깃허브로 전송 ☁️
  - `git push origin 브랜치명` (주의: ** 본인이 만든 브랜치 이름 써주세요!**)
  
## 🔀 6. Pull Request (PR) 보내기
- 검토 요청하기
<img width="1836" height="466" alt="image" src="https://github.com/user-attachments/assets/e63da8d5-42a2-4b6d-8852-2e51157edd30" />
<img width="2770" height="1412" alt="image" src="https://github.com/user-attachments/assets/d3a448a2-5ee9-4ca1-bc22-520bab2d473d" />


