---
layout: single
title:  "[SWEA] 4789. 성공적인 공연 기획"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWS2dSgKA8MDFAVT&categoryId=AWS2dSgKA8MDFAVT&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 박수치는 사람의 수를 셀 cnt를 a[0]으로 초기화 해준다.
2. 고용할 사람을 세기 위한 res를 0으로 초기화 해준다.
3. a[0]을 저장했으니 i가 1부터 len(a)까지 반복문을 만들어준다.
4. 만약 a[i]가 0이라면 더하고 세줄 것도 없으니 continue해준다.
5. 0이 아닐 때 i가 cnt보다 크다면 박수치는 인원이 부족한 것이므로
res에 i-cnt(박수치기 위해 고용해야할 인원)을 더해주고  
cnt에는 최소 i만큼의 박수칠 인원이 필요하므로 i를 더해주고 
a[i]에 해당하는 수만큼 또한 같이 더해준다.
6. 테스트 케이스 번호와 res를 출력해준다.





# 정답 코드
<script src="https://gist.github.com/kghees/856d4dfc8b0625c65118d98f2ee3ae82.js"></script>