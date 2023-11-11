---
layout: single
title:  "[SWEA] 7465. 창용 마을 무리의 개수"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AWngfZVa9XwDFAQU&categoryId=AWngfZVa9XwDFAQU&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=2>




  
  
# 과정
## 1
1. a리스트에 사람들 간의 관계를 저장해준다.
2. 사람들 간의 관계를 확인했나 안했나 확인할 check리스트를 만들어준다.
3. 무리의 수를 셀 cnt를 0으로 정의해준다.
4. i번사람부터 방문하지 않았다면 i번 사람에 대해 관계를 따져준다.  
cnt에 1을 더해준다(dfs()함수 한번 실행하고 나면 무리가 1개있다는 뜻이므로)
5. dfs()함수에서 x에 대해 방문확인(True)해준다.  
a[x]안에 있는 i에 대해 방문하지 않았다면 i에 대해서 dfs(i)(관계를 따져준다)실행한다.
6. 테스트 케이스 번호와 cnt를 출력한다.

## 2
1. a리스트에 사람들 간의 관계를 저장해준다.
2. 사람들 간의 관계를 확인했나 안했나 확인할 check리스트를 만들어준다.
3. 무리의 수를 셀 cnt를 0으로 정의해준다.
4. i번사람부터 방문하지 않았다면 i번 사람에 대해 관계를 따져준다.  
cnt에 1을 더해준다(bfs()함수 한번 실행하고 나면 무리가 1개있다는 뜻이므로)
5. q를 만들어주고 q에 x를 넣어주고 x에 대해 방문확인(True)해준다.
6. a[x]안에 있는 i에 대해 방문하지 않았다면 i에 대해서
방문확인(True)해주고 i를 q에 추가해준다.
7. 테스트 케이스 번호와 cnt를 출력한다.

# 정답 코드
## 1
<script src="https://gist.github.com/kghees/6f34649e3c7037ea692997fa8db19a73.js"></script>
  
    
## 2
<script src="https://gist.github.com/kghees/fb154f202df717fb51e56bf73d046c2d.js"></script>


