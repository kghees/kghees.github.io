---
layout: single
title:  "[SWEA] 4522. 세상의 모든 팰린드롬"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWO6Oao6N4QDFAWw&categoryId=AWO6Oao6N4QDFAWw&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=9&&&&&&&&&&>


  
  
# 과정
1. 팰린드롬인지 확인하기 위한 check를 True로 만들어준다.
2. 문자열 s에 '?'가 없다면   
s와 뒤집은 s가 같다면 테스트 케이스 번호와 Exist를 출력해준다.  
다르다면 테스트 케이스 번호와 Not exist를 출력해준다.
3. 문자열 s에 '?'가 있으면 s[i]가 '?'라면 상관 없으니 continue
s[i]와 s[-i-1]가 같아도 continue해준다.
4. 만약 s[i]와 s[-i-1]이 다른데 s[-i-1]이라면 상관 없으니 continue  
'?'가 아니라면 팰린드롬이 아니니 check = False로 해주고 break해준다.
5. check가 True라면 테스트 케이스 번호와 Exist를 출력해준다.  
check가 False라면 테스트 케이스 번호와 Not exist를 출력해준다.


  




# 정답 코드
<script src="https://gist.github.com/kghees/77397c7485312f3788d7270fcbf22140.js"></script>
      