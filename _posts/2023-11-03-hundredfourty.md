---
layout: single
title:  "[SWEA] 12051. 프리셀 통계"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXmwMidaSLIDFARX&categoryId=AXmwMidaSLIDFARX&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=13>
  
  
# 과정
1. d(오늘 이긴 게임 퍼센트)가 0이 아닌데 g(총 게임 이긴 퍼센트)가 0이라면 오류가 있는 것이므로  
테스트 케이스 번호와 Broken을 출력한다.
2. d(오늘 이긴 게임 퍼센트)가 100이 아닌데 g(총 게임 이긴 퍼센트)가 100이라면 오류가 있는 것이므로  
테스트 케이스 번호와 Broken을 출력한다.
3. d가 맞는 통계인지 확인하기 위해 check를 False로 정의해준다.
4. (i*d)//100 과 (i*d)/100이 성립하면 맞는 통계이므로 
check를 True로 바꾸고 break 해준다.
5. check가 True라면 테스트 케이스 번호와 Possibl을 출력해준다.
  
check가 False라면 테스트 케이스 번호와 Broken을 출력해준다.
 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/2677dce2213851c0e57cf84302d422ad.js"></script>