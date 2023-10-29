---
layout: single
title:  "[SWEA] 10912. 외로운 문자"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXVJuEvqLAADFASe&categoryId=AXVJuEvqLAADFASe&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=6>

  
  
# 과정
1. 결과를 오름차순 정렬하기 위해 s를 정렬해준다.
2. 결과를 넣어줄 리스트 stack을 만들어준다.
3. s에서 stack이 비어있지 않고 stack의 마지막 문자가 i와 같다면 stack에서 pop시켜준다.
4. 아니라면 stack에 i에 해당하는 문자를 추가해준다
5. stack이 비어있지 않다면 테스트 케이스 번호와 공백없이 stack를 출력해준다.  
stack이 비어있다면 테스트 케이스 번호와 Good을 출력해준다.






# 정답 코드
<script src="https://gist.github.com/kghees/4d47fd5aaaf7d85502a83a41156d09e0.js"></script>