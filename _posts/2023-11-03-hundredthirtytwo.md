---
layout: single
title:  "[SWEA] 7584. 자가 복제 문자열"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWpMsQfaCPMDFAQi&categoryId=AWpMsQfaCPMDFAQi&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=12>
  
  
# 과정
1. 결과를 저장할 res를 0으로 정의한다.
2. 규칙을 찾아보면 분열을 몇번하던 k번째 숫자는 같은 것을 알 수 있다.  
1 이 되는 인덱스 :  2, 5, 6, 10, 11, 13, 14  
0 이 되는 인덱스 : 0, 1, 3, 4, 7, 8, 9, 12
0에는 4의 배수가 들어있고 1에는 4의 배수가 아닌 2의 배수들이 들어 있다.  
홀수가 나오면 2의배수나 4의배수로 만족하게끔 k를 만들어주고  
4의배수나 2의 배수가 나오면 0,1로 res를 만들어주고 break해준다.
3. 테스트 케이스 번호와 res를 출력해준다.  
 
  
    
    
# 정답 코드
<script src="https://gist.github.com/kghees/ac94d13b13f22e197961a1fd932aeabe.js"></script>