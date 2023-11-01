---
layout: single
title:  "[SWEA] 1244. [S/W 문제해결 응용] 2일차 - 최대 상금"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV15Khn6AN0CFAYD&categoryId=AV15Khn6AN0CFAYD&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 숫자를 계속 바꿔야 하므로 a를 리스트화 해주고 결과를 저장할 res를 0으로 정의해준다.
2. 최대상금을 확인하기(완전탐색,백트래킹) 위한 함수 money를 정의해준다.
3. cnt가 n(진행횟수)와 같으면 현재 a리스트에 있는 값과 res 값을 비교해 더 큰 값을 저장시키고 return 시켜준다.
4. a[i]보다 a[j]가 크거나 같으면 자리를 바꿔주고 money함수에 i와 1번 바꿨으니 cnt에 1을 더해서 호출시켜준다.
5. 실행 후에는 다른 경우도 고려해야하니 다시 a[i] 와 a[j]의 자리를 바꿔준다.
6. 만약 res가 0이고 cnt가 n보다 작을 경우
k가 2로 나누어진다면 그대로 두고  
k가 1이라면 마지막 수 두개를 바꾸는게 제일 큰 값이므로 바꾸고 money에는 x와 진행횟수를 다 채웠으니 int(n)을 넣고 호출시켜준다.
7. 테스트 케이스 번호와 res를 출력해준다.  

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/844f412b5d49e71f19f5b72d6c29b6df.js"></script>
      