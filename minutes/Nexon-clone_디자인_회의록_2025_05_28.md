
# ✅ 웹 디자인 회의록 정리 (2025년 5월 28일)

## 📌 어제 회의 내용 수정

1. **로그인, 회원가입 페이지 추가 작업 중단**  
   → 해당 기능은 최소 구현만 유지하고, 각자 담당하는 **메인 페이지 작업에 집중하기로 결정**

2. **향후 git 브랜치 네이밍 룰 통일**  
   - 브랜치 이름 형식:  
     - `feature/(이슈번호)` → 기능 작업  
     - `html/(이슈번호)` → HTML 작업  
     - `css/(이슈번호)` → CSS 작업  
   - 예시:  
     - `feature/101`  
     - `html/105`  
     - `css/110`

---

## 📦 Github 작업 절차 및 정리

1. **PR 요청 및 검토 프로세스**
   - 팀장이 조원들의 Pull Request(PR)을 확인
   - 팀장의 로컬 브랜치에서 `pull`로 코드 확인 후 `main` 브랜치와 merge 시도
   - 충돌 여부 확인  
     → **충돌 없음** 확인 시 PR 승인 진행

2. **PR 승인 방법**
   - PR 리뷰어 지정
   - `Approve` 선택
   - `main` 브랜치에 merge
   - **불필요한 브랜치 삭제**

3. **팀장 작업 브랜치 처리**
   - 팀원 PR이 승인되고 `main`에 merge되면, 팀장 브랜치도 필요 시 병합

4. **원격 저장소에서 최신 코드 반영**
   ```bash
   git pull
   ```

5. **로컬 브랜치 정리**
   ```bash
   git branch -d <브랜치명>
   ```

6. **더 이상 연동되지 않는 원격 브랜치 제거**
   ```bash
   git push origin --delete <브랜치명>
   ```

---

## 🧼 기타 변경 사항

1. **CSS 수정**
   - `Common.css`에서 `body`의 `width: 1980px` 속성 제거

2. **.gitignore 파일 정비**
   - [Toptal GitIgnore Generator](https://www.toptal.com/developers/gitignore)에서 제공하는 템플릿 중  
     **IntelliJ 관련 불필요 항목 제거**

---
