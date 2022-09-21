# TIL

## 2022-09-21

### [1] 리눅스 커맨드라인 기초
```
1. pwd // print working directory(현 작업물 저장 경로)
2. cd // change directory(경로 이동)
    > cd ../(상위 폴더로 이동)
3. ls // list
    > -a(숨김파일)<br>
    > -l(자세한 목록)<br>
    > -al(숨김파일 + 자세한 목록)  
```

### [2] vim 사용법
>새로운 파일 만들기
```
1. i(입력모드 전환)  
2. Esc(명령모드로 전환)  
3. 명령어
    > w:저장
    > q:나가기
    > wq:저장 후 나가기)
```

<기타>
```
* clear: 창 깨끗하게
* history: 이전에 썼던 함수들 리스트로 보여줌
* ↑: 이전에 썼던 함수들
```

### [3] commit
>정의
```
1. The 'commit' command is used to save your changed to the local repository.
2. commit 하나는 독립적인 버전을 나타냄
3. The git commit command captures a snapshot of the project's currently staged changes.
4. 스냅샷(사진)과 유사
```
> 언제 커밋을 생성하는가?
```
1. logical한 변경이 있을 때 커밋을 하나 만듦
2. 가능하면 커밋 단위는 작을 수록 좋다.
```