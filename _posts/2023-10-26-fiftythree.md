---
layout: single
title:  "[SWEA] 9700. USB 꽂기의 미스터리"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXDNEA3aaU0DFAVX&categoryId=AXDNEA3aaU0DFAVX&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=3>

  
  
# 과정
1. p,q를 실수형으로 입력 받는다.
2. x를 s1인 경우로 했을때 처음에 뒤집어서 받아야 1번 뒤집었을때 꽂을 수 있으므로 뒤집어서 받을 확률 * 뒤집었을때 꽂힐 확률
3. y를 s2인 경우로 했을 때 처음에 제대로 받을 확률 * 제대로 받아서 안꽂힐 확률 * (1번 뒤집으면 아예 안꽂히니) 2번 뒤집었을때 꽂힐확률
4. y가 x보다 크면 테스트 케이스와 YES 출력 작으면 테스트 케이스와 NO 출력






# 정답 코드
<script src="https://gist.github.com/kghees/cb70042af8d969da0b5912c9953753cc.js"></script>