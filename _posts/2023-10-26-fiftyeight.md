---
layout: single
title:  "[SWEA] 14178. 1차원 정원"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AX_N3oSqcyUDFARi&categoryId=AX_N3oSqcyUDFARi&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=4>

  
  
# 과정
1. d*2+1만큼의 범위를 분무기가 뿌리므로 n에서의 나머지가 없으면  
그대로 n에서 d*2+1을 나눈 몫을 테스트 케이스 번호와 출력한다.
2. 나머지가 있으면 남는 부분이 있으므로 테스트 케이스 번호와  
n에서 d*2+1을 나눈 몫에 +1을 해서 출력한다.







# 정답 코드
<script src="https://gist.github.com/kghees/b6571afbbc8a24da62f9f35990151f65.js"></script>