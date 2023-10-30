---
layout: single
title:  "[SWEA] 9480. 민정이와 광직이의 알파벳 공부"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXAdrmW61ssDFAXq&categoryId=AXAdrmW61ssDFAXq&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=6>


  
  
# 과정
1. 결과 값을 저장할 cnt를 0으로 초기화 해준다.
2. 알파벳을 저장하고 검사할 alpha함수를 만들어준다.
3. 0으로 시작해서 x가 n과 같아지고 ans에서 중복을 제거한 res가 길이가 26이라면(알파벳 수가 26) cnt에 1을 더해준다.
4. 아니라면 alpha에서 a리스트에 있는 값을 골라서 더해준 경우와  
안고르고 넘어간 경우를 고려해준다.
5. 테스트 케이스 번호와 cnt를 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/fed180e0dfb024ed9c6c73cf1fb4cbbe.js"></script>