---
layout: single
title:  "[SWEA] 1928. Base64 Decoder"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PR4DKAG0DFAUq&categoryId=AV5PR4DKAG0DFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1>




  
  
# 과정

1. s에 안에 i문자를 decode에 맞는 숫자들로 바꿔서 x에 저장 하고
ans에 6자리 이진수로 바꿔서 쭉 더해준다.  
zfill: 최소 ()에 있는 값으로 만들기 위해 왼쪽 앞에 0을 추가해준다.
2. a리스트에 ans에서 8자리씩 끊어서 십진수로 바꾸어 저장해준다.
3. a에 있는 i들의 십진수를 각각의 아스키 코드로 변환해서 res에 더해준다.
4. 테스트 케이스 번호와 res값을 출력해준다.


# 정답 코드
<script src="https://gist.github.com/kghees/7da77e4a30c475f4a3e14414261b8dfa.js"></script>
  



