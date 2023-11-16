---
layout: single
title:  "[SWEA] 1948. 날짜 계산기"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PnnU6AOsDFAUq&categoryId=AV5PnnU6AOsDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=2>




  
  
# 과정

1. day에 모든 달의 일의 누적합을 저장한다.
2. res에 (마지막 달 날짜 + 마지막 달 전달까지의 총 날짜) - 
(시작한 달 날짜 + 시작하기 전달까지의 총 날짜) + 1을 해준다. 
3. 테스트 케이스 번호와 res를 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/7451bffe57e526f2c02195d3d06c39da.js"></script>


