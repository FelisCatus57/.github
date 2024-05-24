# Git 및 GitHub 실무 문제

1. **'git config' 명령어를 사용하여 사용자 이름과 이메일을 설정하는 명령어는 무엇인가요?**
   - `git config --global user.name "Your Name"`
   - `git config --global user.email "your.email@example.com"`

2. **기존 디렉토리를 Git 저장소로 초기화하는 명령어는 무엇인가요?**
   - `git init`

3. **새로운 파일을 추가하고 커밋하는 명령어는 무엇인가요?**
   - `git add <file>`
   - `git commit -m "Commit message"`

4. **새로운 브랜치를 생성하고 해당 브랜치로 전환하는 명령어는 무엇인가요?**
   - `git branch <branch-name>`
   - `git checkout <branch-name>`

5. **워킹 디렉토리의 변경사항을 확인하는 명령어는 무엇인가요?**
   - `git status`

6. **원격 저장소를 추가하는 명령어는 무엇인가요?**
   - `git remote add origin <repository-url>`

7. **로컬 커밋을 원격 저장소에 푸시하는 명령어는 무엇인가요?**
   - `git push origin <branch-name>`

8. **원격 저장소의 변경사항을 로컬 저장소로 가져오는 명령어는 무엇인가요?**
   - `git pull origin <branch-name>`

9. **브랜치를 병합하는 명령어는 무엇인가요?**
   - `git merge <branch-name>`

10. **병합 충돌이 발생했을 때 충돌을 해결한 후 커밋하는 과정은 무엇인가요?**
    - 충돌 해결 후: `git add <resolved-files>`
    - `git commit`

11. **작업 중인 변경사항을 임시로 저장하고 나중에 다시 적용하는 명령어는 무엇인가요?**
    - `git stash`
    - 나중에 적용: `git stash pop`

12. **특정 커밋에 태그를 추가하는 명령어는 무엇인가요?**
    - `git tag <tag-name> <commit-id>`

13. **커밋 히스토리를 확인하는 명령어는 무엇인가요?**
    - `git log`

14. **삭제된 파일을 마지막 커밋 상태로 복구하는 명령어는 무엇인가요?**
    - `git checkout -- <file>`

15. **GitHub 웹사이트에서 새로운 저장소를 생성하고 로컬 저장소와 연결하는 과정은 무엇인가요?**
    - GitHub에서 저장소 생성 후:
    - 로컬 저장소에서: `git remote add origin <repository-url>`

16. **다른 사용자의 GitHub 저장소를 Fork하고 변경사항을 반영하기 위한 Pull Request를 생성하는 과정은 무엇인가요?**
    - GitHub에서 저장소 Fork
    - 로컬에 클론 후 변경사항 커밋 및 푸시
    - GitHub에서 Pull Request 생성

17. **GitHub에서 Issue를 생성하고 관리하는 방법은 무엇인가요?**
    - GitHub 저장소에서 Issues 탭 클릭
    - New Issue 클릭 후 Issue 작성

18. **GitHub Actions를 사용하여 CI/CD 파이프라인을 설정하는 방법은 무엇인가요?**
    - 저장소에 `.github/workflows` 디렉토리 생성
    - YAML 파일 작성하여 워크플로우 정의

19. **GitHub 저장소에 협력자를 초대하는 과정은 무엇인가요?**
    - 저장소 Settings 클릭
    - Collaborators & Teams 선택 후 협력자 초대

20. **GitHub에서 Webhook을 설정하는 방법과 이를 통해 자동화할 수 있는 작업의 예시는 무엇인가요?**
    - 저장소 Settings에서 Webhooks 클릭
    - Payload URL 및 이벤트 설정
    - 예시: 푸시 이벤트 발생 시 CI 서버에서 빌드 트리거
