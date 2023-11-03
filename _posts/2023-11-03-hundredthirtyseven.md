---
layout: single
title:  "[SWEA] 13732. 정사각형 판정"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AX8BAN1qTwoDFARO&categoryId=AX8BAN1qTwoDFARO&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=12>
  
  
# 과정
1. 막혀있는 칸을 세주기 위한 cnt를 0으로 초기화 해주고  
정사각형인지 판단하기위한 d 리스트를 만들어준다.
2. a리스트에서 '#'의 개수를 cnt에 저장 d 리스트에 '#'자리에 1을 넣어준다.
3. 정사각형을 판정하기 위한 check()함수를 만들어준다.
4. 아래(down),오른쪽(right)의 개수를 세주고 두 개의 개수가 틀리면 정사각형이 아니니 바로 False를 return해준다.
5. d리스트에 1의 개수가 cnt에 개수와 다르면 False를 return
위의 조건을 모두 만족하면 정사각형이니 True를 return해준다. 
6. check 함수가 True라면 테스트 케이스 번호와 yes 출력해주고  
False라면 테스트 케이스 번호와 no를 출력해준다.

 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/74514357d8e557d362bf72498b0871f7.js"></script>