---
layout: single
title:  "[SWEA] 5603. [Professional] 건초더미"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWXGEbd6cjMDFAUo&categoryId=AWXGEbd6cjMDFAUo&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=6>


  
  
# 과정
1. a리스트의 평균을 x에 저장한다.
2. 경우의 수를 저장할 cnt를 0으로 초기화해준다.
3. a리스트에서 평균 x보다 크다면 cnt에 i - x해서 저장해주고  
평균 x보다 작거나 같다면 cnt에 x-i해서 저장해준다.
4. 테스트 케이스 번호와 큰 값에서도 더해줬고 작은 값에서도 더해줬으니 cnt를 2로 나눠서 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/6ea5510bc6d6f54ba87f898ae06d72a4.js"></script>