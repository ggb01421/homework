---
marp: true
title: Marp
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---
# 20224909 이상호 소프트웨어개론 과제

---

# 목차
1. TOP 명령어
2. PS 명령어
3. JOBS 명령어
4. KILL 명령어
---
# TOP 명령어
TOP란 현재 실행되는 Task(작업)들을 유동적으로 관찰이 가능하다.
윈도우의 작업관리자랑 유사하다.
![height:300px width:600](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FddHQnx%2FbtqEFEw62PN%2F0kcwA8LSu0rpqL15oKURqK%2Fimg.png)

---
# PS 명령어
PS란 Process의 약자로서 지금 사용하고 있는 모든 프로세스를 출력하거나 일부만 제외하고 볼 수 있다.
대신 추가 옵션을 뒤에 붙여야한다. 자주 쓰이는 것들은 -A, -e가 있으며 매우 길다.
![height:300px width:600](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbiRh17%2FbtqECuQIWBZ%2FHRLPxUiTaA5pR3LHCz5QUk%2Fimg.png)

---
# JOBS 명령어
작업의 상태를 표시하는 명령어이며 현재 쉘 세션에서 실행시킨 백그라운드 작업의 목록이 출력된다.
기본적으로는 jobs [옵션][작업번호]로 사용하며 kill 명령어 뒤에도 사용할 수 있다.

---
##### JOBS 명령어
|내용|설명|
|-----|-------|
|Running|작업이 계속 진행중임|
|Done|작업이 완료되어 0을 반환|
|Done(code)|작업이 종료되었으며 0이 아닌 코드를 반환|
|Stopped|작업이 일시 중단|
|Stopped(SIGTSTP)|SIGTSTP 시그널이 작업을 일시 중단|
|Stopped(SIGSTOP)|SIGSTOP 시그널이 작업을 일시 중단|
|Stopped(SIGTTIN)|SIGTTIN 시그널이 작업을 일시 중단|
|Stopped(SIGTTOU)|SIGTTOU 시그널이 작업을 일시 중단|

---
### JOBS 옵션
|옵션|설명|
|-------|-------|
|-l|프로세스 그룹 ID를 state 필드 앞에 출력|
|-n|프로세스 그룹 중에 대표 프로세스 ID를 출력|
|-p|각 프로세스 ID에 대해 한 행씩 출력|
|command|지정한 명령어를 실행|

---

# KILL 명령어
kill 명령어란 프로세스를 제어하는 명령어이다. 안전한 명령어이며 1번부터 64번까지 있고
옵션을 지정하지 않으면 기본적으로 작업 종료로 사용한다.
![height:300px width:550](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbuiEEy%2FbtqEFCsy7Kq%2FcUH9O7CvwnGUmi6Ez21BM0%2Fimg.png) ![height:300px width:550](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fub9Hx%2FbtqEFJdWT2r%2FsK5ryYFiFvw7DVNJfktXaK%2Fimg.png)

---

# 감사합니다.
