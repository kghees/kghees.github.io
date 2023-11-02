---
layout: single
title:  "[SWEA] 7675. 통역사 성경이"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWqPvqoqSLQDFAT_&categoryId=AWqPvqoqSLQDFAT_&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11>


  
  
# 과정
1. 결과 값을 저장할 res 리스트를 만들어준다.
2. 이름의 수를 셀 cnt를 0으로 초기화해준다.
3. '.?!'가 있을 때 마다 문장의 개수를 세어줄 x를 0으로 초기화해준다.
4. c에는 i에 '.?!'가 있다면 제거해주고 i 값을 저장해준다.
5. 첫번째 글자가 대문자이고 나머지 글자가 알파벳이어야 하며 두번째 글자 부터 끝까지 소문자 라면 cnt에 1을 더해준다.
6. i의 마지막에 '.?!'중 하나라도 있다면 한 문장이므로 res에 cnt를 추가해주고 문장 하나가 끝이므로 x에도 1을 더해주고  
다음 문장에서 이름의 수를 세야하니 cnt를 0으로 초기화 해준다.
7. 테스트 케이스 번호와 res를 출력해준다.
 

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/deee15e51b0b74867b9173be8ed9d4c8.js"></script>
      