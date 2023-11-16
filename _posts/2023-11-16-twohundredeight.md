---
layout: single
title:  "[SWEA] 1979. 어디에 단어가 들어갈 수 있을까"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PuPq6AaQDFAUq&categoryId=AV5PuPq6AaQDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1>




  
  
# 과정

1. 들어갈 수 있는 단어의 수를 세기 위한 res를 0으로 정의해준다.
2. 가로,세로에서 k의 길이에 맞는 단어를 세기 위한 x,y를 0으로 만들어준다.
3. 만약 a[i][j]가 1이라면 x에 1을 더해주고   
0이라면 x가 k와 같다면 들어갈 수 있는 단어 이므로 res에 1을 더해준다. 그리고 x를 0으로 초기화 해준다.
4.  만약 a[j][i]가 1이라면 y에 1을 더해주고   
0이라면 y가 k와 같다면 들어갈 수 있는 단어 이므로 res에 1을 더해준다. 그리고 y를 0으로 초기화 해준다.
5. 0을 못만나고 나오는 경우도 있으니 x,y에 대해서 k와 같은지 마지막으로 확인해서 k와 같으면 res에 1을 더해준다.
6. 테스트 케이스 번호와 res를 출력해준다.


# 정답 코드
<script src="https://gist.github.com/kghees/9ccb6f385faa6a4c68ddfce04a734b0c.js"></script>
  



