---
layout: single
title:  "[SWEA] 17642. 최대 조작 횟수"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYj_Dz-6qLgDFASl&categoryId=AYj_Dz-6qLgDFASl&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=13>
  
  
# 과정
1. 최대 조작 횟수를 셀 check라는 함수를 정의해준다.
2. a와 b가 같으면 더하고 뺄 것도 없으므로 0을 return해준다.
3. a가 b보다 크다면 (a에서는 더하기 밖에 안되므로) -1을 return 해준다.
4. b-a가 1이라면 1은 소수가 아니기 때문에 -1을 return해준다.
5. (b-a)%2의 나머지가 1이라면 ((b-a)-1)//2 (최대 횟수로 빼려면 3을 한번빼고 나머지는 다 2로 빼면 되므로) 한 값을 return 해준다.
6. (b-a)%2의 나머지가 0이라면 (b-a)//2 (최대 횟수로 뺴려면 모두 2로 빼면 되므로) 한 값을 return 해준다.
7. 테스트 케이스 번호와 check(a,b)함수를 실행한 값을 출력해준다.
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/9bc4d6d3d14b02f5d0441dc470ff9105.js"></script>