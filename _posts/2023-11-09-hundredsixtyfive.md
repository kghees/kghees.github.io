---
layout: single
title:  "[SWEA] 2819. 격자판의 숫자 이어 붙이기"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV7I5fgqEogDFAXB&categoryId=AV7I5fgqEogDFAXB&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=1>




  
  
# 과정
1. 숫자들을 저장할 res 리스트를 만들어준다.
2. 모든 격자판에 위치를 시작점으로 dfs()함수를 실행시켜준다.
3. 4가지 방향 벡터 dx,dy를 만들어준다.
4. ans에 a[x][y]에 숫자를 더해주고 ans의 길이가 7이면 res에 추가해주고 return해준다.
5. 4가지 방향에 대해 nx,ny가 범위에 있으면 nx,ny에 대해 dfs()함수를 실행시켜준다.
6. res 리스트에서 중복을 제거해준다.(서로 다른 일곱자리의 수)
7. 테스트 케이스 번호와 서로 다른 일곱자리 수의 갯수를 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/f33f0fe00c2894ee51a55eff70357619.js"></script>
  
    


