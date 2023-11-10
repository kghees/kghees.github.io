---
layout: single
title:  "[SWEA] 1211. [S/W 문제해결 기본] 2일차 - Ladder2"
categories: SWEA
tag: [python, D4]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=4&contestProbId=AV14BgD6AEECFAYh&categoryId=AV14BgD6AEECFAYh&categoryType=CODE&problemTitle=&orderBy=INQUERY_COUNT&selectCodeLang=PYTHON&select-1=4&pageSize=10&pageIndex=2>




  
  
# 과정
1. 최소 이동 거리를 저장할 ans를 큰 수로 정의해주고 그때의 출발점을 저장하기 위한 res를 만들어준다.
2. a[0][i]가 1일때의 인덱스 값을 x,y에 넣어주고 cnt를 1로 정의해주고 d도 0으로 정의해준다.
3. x값이 99보다 작을 때까지 만약 d가 0인데 오른쪽이나 왼쪽에 길이 있다면 d값을 변경해주고 d가 1,2일 때 밑에 길이 있다면 d를 0으로 바꾸어준다.
4. x,y 값을 갱신해주고 한칸 왔으니 cnt에 1을 더해주고 x가 99보다 작을 때까지 반복한다.
5. ans값이 cnt 값보다 크면 ans에 cnt 값을 넣고 res에는 그때의 
i(인덱스 값)을 저장한다.
6. 테스트 케이스 번호와 res 값을 출력한다.



# 정답 코드
<script src="https://gist.github.com/kghees/bdbfb9435cf1adc12fed37f653395d10.js"></script>
    


