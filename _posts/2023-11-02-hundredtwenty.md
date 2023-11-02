---
layout: single
title:  "[SWEA] 3282. 0/1 Knapsack"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWBJAVpqrzQDFAWr&categoryId=AWBJAVpqrzQDFAWr&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 부피에 맞게 무게를 넣고 가치를 저장할 d 리스트를 만들어준다.
2. v(부피)는 a[i][0], c(가치)는 a[i][1]이고   
v가 j보다 크면 담을 수 없으므로 d[i][j]에는 그 전의 값을 저장해준다.  
v가 j보다 작거나 같은 경우에는 d[i-1][j-v]에 현재 가치를 더한 값과 이전 값 중 큰 값을 저장 시켜준다.
3. res에 d리스트 중 가장 큰 값을 저장시켜준다.
4.  테스트 케이스 번호와 res를 출력해준다.
 

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/cb783bbf4950dac20c3967ddbd281aac.js"></script>
      