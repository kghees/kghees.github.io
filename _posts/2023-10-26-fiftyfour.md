---
layout: single
title:  "[SWEA] 16910. 원 안의 점"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYcllbDqUVgDFASR&categoryId=AYcllbDqUVgDFASR&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=3>

  
  
# 과정
1. 점의 개수를 담을 cnt를 0으로 초기화 한다.
2. 음수인 점도 고려해야 하므로 for문의 범위를 -n부터 n이 포함되게끔 적어준다.
3. i제곱 + j제곱이 n의 제곱보다 작거나 같으면 cnt에 1을 더해준다.
4. 테스트 케이스 번호와 cnt를 출력해준다.






# 정답 코드
<script src="https://gist.github.com/kghees/c5a87dc6cdd12914cc100858f003fa78.js"></script>