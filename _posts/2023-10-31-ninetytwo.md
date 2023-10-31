---
layout: single
title:  "[SWEA] 1873. 상호의 배틀필드"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV5LyE7KD2ADFAXc&categoryId=AV5LyE7KD2ADFAXc&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 맵을 저장 받을 리스트 a와 전차의 방향의 위치를 저장하기 위한 x,y와 전차의 방향을 저장하기 위한 d를 초기화 해준다.
2. 맵을 입력받으면서 a리스트에 추가해주고 맵에서의 전차 방향의 위치를x,y에 저장 전차 방향을 d에 저장시켜준다.
3. 사용자 입력이 'S' 일때 방향이 위('^')라면 위쪽방향에 벽돌이 있다면 부셔지므로 평지로 바꿔주고 강철이라면 부수지 못하므로 break해준다.  
4. 나머지(아래('v'), 왼쪽('<'),오른쪽('>'))에도 동일시 하게 적용시켜준다.
5. 사용자 입력이 'U'일때 d를 위('^') 방향으로 저장 후 바로 위칸이 범위를 벗어난다면 현재 칸에 d방향을 넣고 continue해주고  
위칸이 평지라면 현재칸을 평지로 바꿔주고 위칸에 전차 방향을 
위('^')방향으로 바꿔준다.
6. 나머지 사용자 입력이 'D','L','R' 일 때도 동일시하게 적용시켜준다.
7. 테스트 케이스 번호와 바뀐 맵을 출력시켜준다.





# 정답 코드
<script src="https://gist.github.com/kghees/865954d6104eae4394a717780dfa3a22.js"></script>