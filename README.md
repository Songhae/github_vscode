# github_vscode
Git, GitHub, VSCode 활용방법

1. Git 사용하기
  - Git 필수 기초
    . clone, add, commit, push, pull
  - GitHub 사용
    . SSH key 생성 및 활용
2. VS Code 활용
   - Settings
   - extension
   - GitHub 연동
   - Jupyter

## 전체적인 순서

1. git 설치 후 기본 설정
   - git config --global user.name "이름"
   - git config --global user.email xxxx@xxxxx.com
3. Local에서 SSH Key 생성 --> Github에 Key 등록
   - ssh-keygen -t rsa
   - cd .ssh
   - id_rsa.pub 키 값 복사
   - gitgub >  Settings > SSH Key 등록
4. github에서 Repository 생성
5. 주소 복사: git@github.com:zettakim/xxxxxx.git
6. local에 Ditrectory 만들고
7. git clone git@github.com:zettakim/xxxxxx.git 하위 데렉토리 생성됨 xxxxxx
8. git 기초
   - git add .
   - git commit -m "message"
   - git push
   - git pull
  
---------------------------
### vscode
1. settings / github에 설정 Sync
2. git아이콘 클릭하야 Repository clone
3. Source Control에서
   - "+" 버튼 (git add)
   - 메세지 넣고 commit (git commit)
   - Sync (git push)
