---
layout: single
title:  "[SWEA] 10804. 문자열의 거울상"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXTC0x16D8EDFASe&categoryId=AXTC0x16D8EDFASe&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=3>

  
  
# 과정
1. 거울에 비친 모습을 저장할 리스트 res를 만들어준다.
2. s에서 i가 b이라면 d로 바꿔서 res에 추가해준다.
3. s에서 i가 p이라면 q로 바꿔서 res에 추가해준다.
4. s에서 i가 q이라면 p로 바꿔서 res에 추가해준다.
5. s에서 i가 d이라면 b로 바꿔서 res에 추가해준다.
6. 뒤집어서 저장되었으므로 res를 뒤집어서 저장해준다.
7. 테스트케이스 번호와 공백없이 res를 출력한다.






# 정답 코드
<script src="https://gist.github.com/kghees/1b4e6fa17d583fae78b7e43775d27cf6.js"></script>