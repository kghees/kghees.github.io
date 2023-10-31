---
layout: single
title:  "[SWEA] 2817. 부분 수열의 합"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV7IzvG6EksDFAXB&categoryId=AV7IzvG6EksDFAXB&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 경우의 수를 세어준 cnt를 0으로 초기화해준다.
2. a리스트의 수를 넣어서 합을 판단할 ans 리스트를 만들어준다.
3. 부분 수열의 합을 판단할 함수 part_sum을 만들어준다.
4. ans리스트의 합이 k와 같다면 cnt에 1을 더해준다.
5. x부터 n까지 ans에 a리스트의 수를 하나씩 추가해주고 i+1로(현재썼던 수 제외하기위해) part_sum함수를 재귀시키고 돌아오게되면 다음 판단을 위해 ans에서 pop해준다.
6. 테스트 케이스 번호와 cnt를 출력시켜준다.





# 정답 코드
<script src="https://gist.github.com/kghees/470570271e99c0ce166e3d8bf920b446.js"></script>