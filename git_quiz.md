# git 기초 Quiz
## 1. git의 사전적 정의는 "(중앙) 버전 관리 프로그램"이다.
   - 답 : X
   - 이유 : 분산 버전 관리 프로그램이다.
     - 중앙집권 : 중앙 서버 컴퓨터에 버전이 모여 있는 형태
     - 분산 : 중앙 서버 / 각각의 컴퓨터 모두에 버전이 있는 상태
     - ![image](https://www.notion.so/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Ff2678325-6f7b-4a25-b188-86c42030d6d5%2Fb5880f8a-d9c6-436f-bb1b-2f64d97007d0%2FUntitled.png%3FspaceId%3Df2678325-6f7b-4a25-b188-86c42030d6d5?table=block&id=2cb611ac-3a00-8050-8411-f3edd2726c4a&cache=v2)
## 2. git의 3공간은 working directory, staging area, repository 이다.
    - 답 : O
    - 이유 : git의 3공간에는
      - 작업공간인 working directory
      - 대기공간인 staging area(index)
      - 커밋들이 담겨 있는 공간인 repositry(.git/)가 있다.
## 3. github 에 버전을 저장하기 위해 git commit 명령어를 쓴다.
    - 답 : X
    - 이유 : git commit 명령어는 로컬 저장소에 저장하기 위함이다
    - gitgub 은 버전 관리 호스팅 서비스
    - git commit은
      - **변경사항의 기록**을 남겨서
      - 버전관리를 할 수 있도록 합니다.
      - 따라서 저장(save)보다는 기록(commit)에 가깝다.
## 4. git log 를 통해 버전 기록들의 목록을 확인할 수 있다.
    - 답 : O
    - 이유 : git log 는 커밋의 내역(ID, 작성자, 시간, 메세지 등)을 조회할 수 있는 명령어이다
            git log를 통해, 이전에 남긴 변경사항의 기록들을 확인할 수 있습니다.
            변경사항의 내역은 육하원칙에 따라 정리되어 있기 때문에
            보편적으로 'git log --oneline' 옵션을 함께 사용합니다.

## 5. 버전을 기록하는 프로세스는 git add -> git commit 이다.
    - 답 : O
    - 이유 : 버전 기록을 위해서는 3공간을 오갈 수 있는 'git add', 'git commit' 명령어를 사용한다.
        - 그 외 명령의 목적은 다음과 같다.
            git log : 버전의 기록 내역 확인
            git status : 파일의 상태를 살핀다.

## 6. 변경사항은 6하원칙에 따라 직접 남겨야 한다.
    - 답 : X
    - 이유 : 왜(why)의 대한 정보만 커밋 메세지를 통해 남기면 된다.
            나머지 누가, 언제, 무엇을은 버전관리프로그램인 git이 자동으로 채워준다.