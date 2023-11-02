---
layout: single
title:  "[SWEA] 15612. 체스판 위의 룩 배치"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AYOBfxwaAXsDFATW&categoryId=AYOBfxwaAXsDFATW&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=10>


  
  
# 과정
1. 룩의 수를 셀 res를 0으로 초기화해주고 chess판 위에 룩이 잘 배치 되었는지 확인할 check를 True라고 정의해준다.
2. a[i][j]가 룩이라면 res에 1을 더해주고 chess함수에서 열과 행에 다른 룩이 없나 검사시켜준다.  
만약 True라면 계속 진행하고 False라면 check에 False를 넣고 반복문을 break해준다.
3. 방향벡터 dx,dy를 만들어준다.
4. 열과 행에 다른 룩이 있나 검사할 chess함수를 정의해준다.
5. chess함수에서 열과 행의 검사가 끝났을때 '.'의 갯수가 14개 라면 룩이 하나인 것이므로 True를 return해주고  
14개가 아니라면 False를 return해준다.
6. check가 True이고 res(총 룩의 수)가 8 이라면  
테스트 케이스 번호와 yes를 출력해준다.  
아니라면 테스트 케이스 번호와 no를 출력해준다.
 

  



  



# 정답 코드
<script src="https://gist.github.com/kghees/f4ad9f958dd3f05a0a964ac35bc5a7ef.js"></script>
      