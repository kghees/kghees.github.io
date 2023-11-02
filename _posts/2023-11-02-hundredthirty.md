---
layout: single
title:  "[SWEA] 4579. 세상의 모든 팰린드롬 2"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWQAz7IqAH8DFAWh&categoryId=AWQAz7IqAH8DFAWh&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=11>


  
  
# 과정
1. 팰린드롬인지 판단할 check를 True로 정의한다.
2. s[i]와 s[-i-1]이 다를때 s[i]와 s[-i-1]이 모두 '*'가 아니라면 팰린드롬이 될 수 없으니 check에 False를 정의하고
if문을 break해준다.
3. check가 True라면 테스트 케이스 번호와 Exist를 출력해준다.  
False라면 테스트 케이스 번호와 Not exist를 출력해준다.  


 




# 정답 코드
<script src="https://gist.github.com/kghees/26907d546168ba04ba5e2ee836c95610.js"></script>