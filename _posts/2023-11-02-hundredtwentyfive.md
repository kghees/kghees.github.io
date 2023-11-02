---
layout: single
title:  "[SWEA] 13428. 숫자 조작"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AX4EJPs68IkDFARe&categoryId=AX4EJPs68IkDFARe&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11>


  
  
# 과정
1. 두 문자를 바꿀 인덱스를 추출하기 위한 ans 리스트를 정의한다.
2. 문제에서 요구하는 m1(최소값) 와 m2(최대값) 를 현재의 n값을 정수형으로 변환하여 초기화한다.
3. itertools.combinations() 모듈을 통해 각 인덱스에서 2개를 뽑아 두 문자를 바꾼다.
4. 만약 제일 앞 숫자가 0이라면 다시 바꾼다.
5. m1,m2와 바뀐 n과 계속 비교해 m1,m2값을 저장시켜준다.
6. 다음 실행을 위해 다시 바꾼 값을 원상복귀 시켜준다.
7. 테스트 케이스 번호와 m1,m2를 출력한다.


 

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/83b310d0057211f240707f26d52bea90.js"></script>
      