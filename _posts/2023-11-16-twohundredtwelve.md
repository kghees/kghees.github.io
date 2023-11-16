---
layout: single
title:  "[SWEA] 1983. 조교의 성적 매기기"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PwGK6AcIDFAUq&categoryId=AV5PwGK6AcIDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=2>




  
  
# 과정

1. 10개의 평점을 score리스트에 저장해준다.
2. 평점을 계산해 num 리스트에 넣어준다.
3. res에 num리스트를 내림차순 정렬해 저장해준다.
4. x에 k번째 사람의 점수 순위를 저장한다.  
(n/10명에게 동일한 평점 부여 가능이므로 n//10으로 나눈 몫을 저장)
5. 테스트 케이스 번호와 k번째 사람의 score를 출력해준다.



# 정답 코드
<script src="https://gist.github.com/kghees/b3bcc8bcce25d80c674460410a570ea5.js"></script>


