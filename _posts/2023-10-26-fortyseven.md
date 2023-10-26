---
layout: single
title:  "[SWEA] 3456. 직사각형 길이 찾기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWFPmsqqALwDFAV0&categoryId=AWFPmsqqALwDFAV0&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=3>

  
  
# 과정
1. a,b,c가 모두 같으면 정사각형이므로 a,b,c중 아무거나 출력한다.
2. 1번조건이 아니고 a,b가 같으면 c와 같은 길이의 변이므로 테스트 케이스 번호와 c를 출력한다.
3. 1,2번 조건이 아니고 b,c가 같으면 a와 같은 길이의 변이므로 테스트 케이스 번호와 a를 출력한다.
4. 1,2,3번 조건이 아니고 a,c가 같으면 b와 같은 길이의 변이므로 테스트 케이스 번호와 b를 출력한다.





# 정답 코드
<script src="https://gist.github.com/kghees/4371d0666ddd5641f7313c9a7403c354.js"></script>