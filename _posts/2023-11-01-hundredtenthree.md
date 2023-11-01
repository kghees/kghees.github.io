---
layout: single
title:  "[SWEA] 3304. 최장 공통 부분 수열"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWBOHEx66kIDFAWr&categoryId=AWBOHEx66kIDFAWr&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. a,b 문자열의 길이를 x,y에 넣어준다.
2. x,y로 2차원 리스트 d를 만들어 준다.
3. a의 문자와 b의 문자가 같으면 d[i][j]에 d[i-1][j-1]+1한 값을 더해준다.
4. 다르다면 d[i-1][j](바로 위), d[i][j-1](왼쪽)보다   
큰 값을 d[i][j]에 넣어준다.
5. 테스트 케이스 번호와 d[x][y]를 출력해준다.  
  

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/279601656-0ac7a92e-093b-47b8-8c85-2a80ec38ed5d.png)



  




# 정답 코드
<script src="https://gist.github.com/kghees/9c7c29a469f740d68d52fea51085a145.js"></script>
      