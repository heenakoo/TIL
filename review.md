## 1. git 명령어 


* **git init**: 저장소 초기화하는 명령어
* **touch 파일명.확장자**: 파일 생성
* **git commit -m'메시지'**: git commit (버전기록)
* **git add 파일명.확장자**: 원하는 파일 모음
* **git status**: 현재까지의 저장소에 있는 파일의 상태 
* **git log**: 현재 저장소에 기록된 커밋을 조회
* **git remote add origin http://github.com/     /      .git**: git 원격저장소에 추가
* **git push origin main**: git 원격 저장소로 보냄 push origin/main 으로
* **git remote rm origin**: 삭제
* **git remote -v**: 원격 저장소 목록 조회
* **git config --global core.editor "code --wait”**: git commit 을 하고 내용을 더 길게 적을 수 있고  종료하면 자동적으로 커밋됨. 


### 2. git commit to github 까지 보낼 때 과정


* 보내고자 하는 git add 파일명.확장자 터미널에 입력 
* git commit -m'메시지' 입력
* git remote add origin http://github.com/github username/저장소이름.git 입력
* git push origin main 터미널 입력
* git status 로 중간 중간 확인해보기!!


### 3. Github 새 저장소 생성 방법


* github 나의 프로필 이름 클릭 후 
* 상단의 Repositories 버튼 클릭
* 초록색 버튼 'New' 버튼 누른 후 생성


### 4. Git 사용시 메세지 뜻 


* **tracked**: 이전부터 버전으로 관리되고 있는 파일 상태
* **untracked**: 한번도 커밋된 적이 없는 파일 (파일을 새로 만든 경우)
* **Changes not staged for commit**: 변경된 부분이 커밋을 하기 위한 staged가 되지 않은(1통)
* **nothing to commit, working tree clean**: 아직 변경할 사항이 없고 커밋할게 없다.(1통/2통X)
* **modified**: Changes not staged for commit
* **staged**: Changes to be commited

### 5. Branch

* **git branch 브랜치 이름**: Branch 생성
* **git checkout 브랜치 이름**: Branch 이동
* **git merge 합칠 파일명 이름**: Branch 병합


#### Branch 병합할 때


* git checkout main 입력 후 
* git merge 합칠 파일명 이름 (메인으로 가서)
* 병합하고 브랜치는 삭제 하면 됨.(병합하면서 자동으로 commit 됨.)


### Pull request (Fork 버튼을 그 전에 먼저 누를 것)


-> 프로젝트 협업시 github 에서 pull request 버틑ㄴ을 누르면 본인의 작업물을 가져가달라는 의미로 누르는 버튼. (관리자가 작업물을 보고 merge request 라는 버튼을 누르면 github 내에서 합쳐짐) 

* **git clone url**: 원격 저장소에 있는 협업 프로젝트, 외부 오픈 소스 참여
* **git pull**: 프로젝트 개발 중 다른 사람 커밋 받아오기
* **git push**: 내가 한 로컬 프로젝트 개발 공유시




