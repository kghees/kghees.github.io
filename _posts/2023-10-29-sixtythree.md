---
layout: single
title:  "[SWEA] 10200. 구독자 전쟁"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AXMCXV_qVgkDFAWv&categoryId=AXMCXV_qVgkDFAWv&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=4>

  
  
# 과정
1. 모두 구독하는 최대 사람의 수는 P채널과 T채널 구독하고 있는 사람수 중 더 작은 사람 수를 구해주면 되므로 x에 저장
2. 모두 구독하는 최소 사람의 수는 n이 P채널과 T채널 더한거 보다 작거나 같으면 넘은수는 모두 구독이므로 P채널과 T채널 더한거에서 n을 빼주고 아니라면 0을 저장해준다.
3. 테스트 케이스 번호와 최대구독자 수와 최소 구독자수를 출력한다.







# 정답 코드
<script src="https://gist.github.com/kghees/ea8eced66e919de43175193e7481e081.js"></script>