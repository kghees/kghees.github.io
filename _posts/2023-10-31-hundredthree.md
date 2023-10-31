---
layout: single
title:  "[SWEA] 14361. 숫자가 같은 배수"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYCnY9Kqu6YDFARx&categoryId=AYCnY9Kqu6YDFARx&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. 같은 배수를 만들 수 있는지를 표시하기 위한 check를 False로 만들어준다.
2. 배수 곱을 위한 num = n 으로 만들어주고 i를 2로 만들어준다.
3. num에 리스트화 한 n의 배수를 넣고 i에 1을 더해준다.
4. 재배열로 배수를 만들 수 있냐는게 문제 이므로 n의 길이와 num의 길이가 달라지면 바로 break해준다.
5. 만약 중복을 제외한 n과 num이 같다면 재배열해서 배수를 만들수 있으므로 check를 True로 하고 break해준다.
6. check가 True라면 테스트 케이스 번호와 possible를 출력해준다.
7. check가 False라면 테스트 케이스 번호와 impossible를 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/53fa70c809f8b12e4708b722b475174a.js"></script>
      