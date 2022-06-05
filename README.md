# 과제
***********
### top
+ 시스템의 상태를 전반적으로 가장 빠르게 파악 가능(CPU, Memory, Process)

+ 옵션 없이 입력하면 interval 간격(기본 3초)으로 화면을 갱신하며 정보를 보여줌

+ 순간의 정보를 확인하려면 -b 옵션 추가(batch 모드)

+ -n : top 실행 주기 설정(반복 횟수)

+ a : 메모리 사용량에 따라 정렬

+ shift + t : 프로세스가 돌아가고 있는 시간 순

+ shit + m : 메모리 사용률 내림차순

+ shift + p : CPU 사용률 내림차순

[출처](https://zzsza.github.io/development/2018/07/18/linux-top/)
*****************
### ps
+ps명령어는 현재 실행중인 프로세스 목록을 보여준다.

|옵션|설명|
|:---:|:---:|
|-e| 모든 프로세스를 출력해 준다.|
|-f| 풀 포맷으로 보여준다.(UID, PID 등)|
|-l| 긴 포맷으로 보여준다.|
|p, -p| 특정 PID의 프로세스를 보여준다.|
|-u | 특정 사용자의 프로세스를 보여준다.|

[출처](https://arer.tistory.com/150)
******
### jobs
<img src="https://user-images.githubusercontent.com/106831414/172044061-b2d02308-68c6-48fa-8b01-6097dcc721c4.jpeg" width="640" height="480">

[출처](https://www.leelab.co.kr/bbs/board.php?bo_table=linux&wr_id=10)
******
### kill

+ kill명령어는 대부분 프로세스를 죽일때(종료시킬때) 사용합니다.

+ kill [-옵션 or 시그널] PID

********
### 메크로 in vim에디터


