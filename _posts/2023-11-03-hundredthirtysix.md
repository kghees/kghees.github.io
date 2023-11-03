---
layout: single
title:  "[SWEA] 5642. [Professional] 합"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWXQm2SqdxkDFAUo&categoryId=AWXQm2SqdxkDFAUo&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=12>
  
  
# 과정
1. 연속된 수의 합을 저장할 d 리스트를 만들어준다.
2. d[i]는 전에 연속된 수의 합에 현재수를 더한 것과 현재 수 중 큰 값을 저장시켜준다.  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/280252356-de6adcfc-819d-44fc-be61-3930ec511a6e.png)

3. 테스트 케이스 번호와 d에서 가장 큰 수를 출력해준다.

 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/b30c8e06f978a612cd4a0c77615163bb.js"></script>