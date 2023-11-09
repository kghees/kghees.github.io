---
layout: single
title:  "[SWEA] 1210. [S/W 문제해결 기본] 2일차 - Ladder1"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14ABYKADACFAYh&categoryId=AV14ABYKADACFAYh&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정
## 1
1. 결과 값을 저장할 res를 0으로 정의해준다.
2. 방향이 아래쪽,왼쪽,오른쪽밖에 없으니 3가지 방향 벡터를 만들어준다.
3. x,y에 시작점의 좌표를 넣어주고 방향 벡터 값을 넣을 d를 0으로 정의해준다.
4. x가 99보다 작을경우에 계속 반복 한다.
5. d가 0일때   
사다리 왼쪽에 가는 길이 있는 경우 d를 2로 바꿔준다.  
사다리 오른쪽에 가는 길이 있는 경우 d를 1로 바꿔준다.
6. 그 외의 경우에는 사다리 아래쪽에 가는 길이 있는경우 d를 0으로 바꾸어 준다.
7. x와 y에 d방향 값들을 더해준다.
8. x,y좌표에 있는 값이 2일 경우 res에 i를 넣고 break해준다.
9. 테스트 케이스 번호와 res 값을 출력해준다.

## 2
1. 사다리의 도착지부터 거꾸로 올라가기 위해 x,y에 도착 지점의 좌표를 넣어준다.
2. x좌표 값이 0이 아니라면 계속 반복한다.
3. 현재 위치에서 오른쪽에 길이 있을 경우 길이 있는 곳 까지 y좌표에 1을 더해주고 끝나면 x좌표에서 1을 빼준다.(안빼면 왼쪽에 길이 있다고 판단하므로)
4. 현재 위치에서 왼쪽에 길이 있을 경우 길이 있는 곳 까지 y좌표에 1을 빼주고 끝나면 x좌표에서 1을 빼준다.(안빼면 오른쪽에 길이 있다고 판단하므로)
5. 왼쪽,오른쪽에 길이 없으면 위쪽으로 올라가야하므로 x좌표에서 1을 빼준다.
6. 테스트 케이스 번호와 출발지점의 y좌표값을 출력한다.

# 정답 코드
## 1
<script src="https://gist.github.com/kghees/0b32c5c535ad2ef89fd90e61dac3e69c.js"></script>
  
    
## 2
<script src="https://gist.github.com/kghees/7e0975d1e590fdba87ec2e8e932e02ae.js"></script>


