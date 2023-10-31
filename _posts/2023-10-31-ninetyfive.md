---
layout: single
title:  "[SWEA] 9280. 진용이네 주차타워"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AW9j74FacD0DFAUY&categoryId=AW9j74FacD0DFAUY&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=8>


  
  
# 과정
1. 단위무게당 금액을 money에 차량의 무게를 weight에 입력받는다.
2. 주차공간을 park에 대기하는 곳을 위해 wait 리스트를 만들어주고
요금을 더할 res를 0으로 초기화 시켜준다.
3. 주차장 출입 순서에서 i가 음수 일 때 park에서의 abs(i)의 인덱스를 index에 저장시켜준다.
4. i가 음수 일 때 wait에 대기하는 차가 있으면 a에 wait에 있는 차를 pop해주고 park[index]에 해당하는 곳에 a 값을 넣어주고
차가 들어왔으니 a의 주차 요금을 res에 더해준다.
5. wait에 대기하는 차가 없으면 park[index]를 0으로 만들어준다.
6. i가 양수 일 때 park리스트에 0이 없으면 주차공간이 없으니
wait으로 i 값을 추가해준다.
7. park리스트에 0인 값이 있다면 0인 곳의 인덱스를 index에 넣어주고 park[index]를 i로 바꿔준다.  
차가 들어왔으니 i의 주차요금을 res에 더해준다.
8. 테스트 케이스 번호와 res를 출력시켜준다.





# 정답 코드
<script src="https://gist.github.com/kghees/fc9397dbeead0761a4654f8f8b7a326d.js"></script>