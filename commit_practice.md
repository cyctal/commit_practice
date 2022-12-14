## Git 기초 실습 - 문제풀기

> 아래에 있는 각각의 문제에 대해 답과 이유를 작성하시오.
> 한 문제를 풀 때마다 커밋을 저장하시오. 커밋 메시지는 "solve 문제번호 problem"의 형태로 저장하시오.



1. Git과 Github는 같다. (맞으면 O, 틀리면 X)

   - 답 : x
   - 이유 : git 분산 버전 관리 **프로그램**이며, github는 git 저장소를 호스팅하는 **웹 서비스다.**

   

2. 터미널 명령어 `cd .`은 현재 위치의 부모 폴더로 이동하라는 의미이다. (맞으면 O, 틀리면 X)

   - 답 : x
   - 이유 : 
     - `cd ..`에서 ..은 상위(부모) 디렉토리를 의미한다. 따라서 이것이 상위 폴더로 이동하라는 명령어이다. 
     - .은 현재 디렉토리를 의미한다.



3. 마크다운 문법에서 글씨의 크기를 키우고 싶다고해서 본문을 제목으로 지정하면 안된다. (맞으면 O, 틀리면 X)
   - 답 : o
   - 이유 : 마크다운 문법에서 각 역할을 부여하는 것이기 때문에 본문을 제목으로 지정하면, 혼란을 줄 수 있다. (제목을 지정하는 것은 크기를 키운다기보다 역할을 어기는 것이므로 적절하지 않다.) 마크다운 문법에서는 글씨 크기를 변경할 수 없고 다른 방법을 써야 한다.



4. Git의 3가지 공간에는 Working Directory, Staging Area, Commits이 있다. (맞으면 O, 틀리면 X)
   - 답 : x
   - 이유 : git의 세 가지 공간에는 working directory, staging area, repository가 있다. repository는 commits가 존재하는 공간이다.



5. Commit ID는 중복 가능하다. (맞으면 O, 틀리면 X)
   - 답 : x(괄호 안은 오답 o)
   - 이유 : commit ID는 고유한 값이어야 각 commit을 구분할 수 있기 때문 (확률이 극도로 낮기는 하지만 이론상으로는 중복가능하다.)