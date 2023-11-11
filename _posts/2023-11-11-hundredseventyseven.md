---
layout: single
title:  "[SWEA] 1486. 장훈이의 높은 선반"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV2b7Yf6ABcBBASw&categoryId=AV2b7Yf6ABcBBASw&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=3>




  
  
# 과정

1. 탑의 높이의들을 저장하고 높이들의 합을 구할 때 사용할 
ans 리스트를 만들어준다. 
2. 높이가 b이상인 탑과 높이가 b인 탑과의 차이가 가장 작은 값을 저장할 cnt를 큰 값으로 만들어준다.
3. ans리스트의 합이 b보다 크거나 같을때 cnt의 값과 sum(ans)-b 값중 최소 값을 cnt에 저장시켜준다.
4. 모든 탑 높이의 조합을 구해준다.
5. 테스트 케이스 번호와 탑의 차이의 최소 값을 출력한다.



# 정답 코드
<script src="https://gist.github.com/kghees/c33ea2c7e565ad77cebf23fef48f2813.js"></script>
  



