---
layout: single
title:  "[SWEA] 1959. 두 개의 숫자열"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PpoFaAS4DFAUq&categoryId=AV5PpoFaAS4DFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=2>




  
  
# 과정

1. 최대 값을 저장할 res를 0으로 정의해준다.
2. b가 a보다 클 때는  
a리스트를 옮겨가면서 x에 arr과 brr리스트 값의 곱의 합을 넣어주고  
res에 최대 값을 저장해준다.
3. a가 b보다 클 때는  
b리스트를 옮겨가면서 x에 arr과 brr리스트 값의 곱의 합을 넣어주고  
res에 최대 값을 저장해준다.
4. 같을 때는 res에 바로 arr과 brr리스트의 값의 곱을 더해준다.
5. 테스트 케이스 번호와 res값을 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/ba78e341007f633fe7eb97b64464cc4e.js"></script>


