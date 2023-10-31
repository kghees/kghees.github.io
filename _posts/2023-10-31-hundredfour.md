---
layout: single
title:  "[SWEA] 1860. 진기의 최고급 붕어빵"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AV5LsaaqDzYDFAXc&categoryId=AV5LsaaqDzYDFAXc&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9>


  
  
# 과정
1. 손님들이 들어온 순서를 오름차순 정렬해준다.
2. 붕어빵을 팔 수 있을지 확인하는 check를 True로 만들어준다.
3. x에 손님이 왔을때 붕어빵이 만들어져 있고 팔았는지를 계산해 넣어준다.
4. x가 0보다 작으면 붕어빵을 팔 수 없음이므로 check에 False로 해주고 break해준다.
5. check가 True라면 테스트 케이스 번호와 Possible를 출력해준다.
6. check가 False라면 테스트 케이스 번호와 Impossible를 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/759dc6fc4b9d14cca30bca50a7e44413.js"></script>
      