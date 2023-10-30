---
layout: single
title:  "[SWEA] 4047. 영준이의 카드 카운팅"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWIsY84KEPMDFAWN&categoryId=AWIsY84KEPMDFAWN&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=7>


  
  
# 과정
1. 스페이스,다이아,하트,클로버 각각 13장씩 있다고 했으니  
s,d,h,c를 각각 13으로 초기화 해준다.
2. 겹치는 카드가 있나 검사할 check를 True로 설정해준다.
3. 3자리씩 표현되기 때문에 3개씩 띄어서 검사를 해주고 각각 카드에 대해서 중복에 대해서도 검사해주고 없으면 s,d,h,c에 해당하는 카드에서 1씩 빼준다.
4. 중복이 있다면 check를 False로 바꾸고 break해준다
5. check가 True라면 테스트 케이스 번호와 s,d,h,c를 출력해준다.
6. False라면 테스트 케이스 번호와 ERROR를 출력해준다.






# 정답 코드
<script src="https://gist.github.com/kghees/8cf9c5b5dd2b8939d6e141b7f939cf21.js"></script>