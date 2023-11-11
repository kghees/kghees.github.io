---
layout: single
title:  "[SWEA] 1231. [S/W 문제해결 기본] 9일차 - 중위순회"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV140YnqAIECFAYD&categoryId=AV140YnqAIECFAYD&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=2>




  
  
# 과정
1. 정점을 저장할 tree 리스트를 만들어준다.
2. 번호 순서에 맞게 정점들을 tree리스트에 저장시켜준다.
3. inorder(중위 순회)함수를 만들어준다.
4. inorder(x*2) = 왼쪽 자식, tree[x] = 루트, 
inorder(x*2+1) = 오른쪽 자식 
5. 테스트 케이스 번호와 중위 순회한 결과 값을 출력한다.




# 정답 코드
<script src="https://gist.github.com/kghees/fc433b6d078c340d20c34acf2cedd5a6.js"></script>
    


