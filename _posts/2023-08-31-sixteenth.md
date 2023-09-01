---
layout: single
title:  "[Algorithm] 다이나믹 프로그래밍(Dynamic Programming)"
categories: Concept
tag: [Algorithm]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---
이번 포스팅에서는 다이나믹 프로그래밍(Dynamic Programming)에 대해서 알아보겠습니다.  


# 다이나믹 프로그래밍(Dynamic Programming) 이란?  
DP, 즉 다이나믹 프로그래밍(또는 동적 계획법)은 기본적인 아이디어로   
하나의 큰 문제를 여러 개의 작은 문제로 나누어서 그 결과를 저장하여   
다시 큰 문제를 해결할 때 사용하는 것으로  
큰 문제를 작은 문제로 나누어서 푸는 알고리즘이라고 이해하면 쉬울 것이다.
  


# 다이나믹 프로그래밍(Dynamic Programming)의 사용 조건  
1. Overlapping Subproblems(겹치는 부분 문제)  

DP는 기본적으로 문제를 나누고 그 문제의 결과 값을 재활용해서 전체 답을 구한다. 
그래서 <span style="color:red">동일한 작은 문제들이 반복하여 나타나는 경우에 사용이 가능</span>하다.  


2. Optimal Substructure(최적 부분 구조)  

<span style="color:red">부분 문제의 최적 결과 값을 사용해 전체 문제의 최적 결과를 낼 수 있는 경우</span>를 의미한다. 
그래서 특정 문제의 정답은 문제의 크기에 상관없이 항상 동일하다!
  
    
      
# 다이나믹 프로그래밍(DP) 사용하기
1) DP로 풀 수 있는 문제인지 확인한다.
2) 문제의 변수 파악
3) 변수 간 관계식 만들기(점화식)
4) 메모하기(memoization or tabulation) - 메모이제이션
5) 기저 상태 파악하기
6) 구현하기

## 구현하기
구현하기 에는 2가지 방식이 있다.
① Top - Down 방식
- 큰 문제를 작은 문제로 쪼개가면서 풀다가 다시 합쳐서 해결
- 재귀방식으로 구현
  

② Bottom - up 방식
- 문제를 크기가 작은 문제부터 차례대로 푼다.
- 문제의 크기를 조금씩 크게 만들면서 문제를 점점푼다.
- 작은 문제를 풀면서 왔기 때문에, 큰 문제는 항상 풀 수 있다.
- 반복하다 보면 가장 큰 문제를 풀 수 있다.
- 주로 반복문으로 구현

# 기타 내용
<span style="color:blue">Q. 두 가지 방법(Top-Down vs Bottom-Up) 중 더 나은 것이 있는지, 하나만 가능한 경우가 있는지?</span>  
  
A. 두 방법 중 어느 것이 시간적으로 더 효율이 있는지 묻는 데 그 답은 <span style="color:red">'알수 없다'</span>이다.  

또한, 2가지 방법 중 2가지를 모두 사용하지는 못하고 하나만 사용할 수 있는 경우가 있느냐는 질문에는 <span style="color:red">'있다'</span> 라고 할 수 있다. 
하지만 그것은 DP에 익숙해지고 나서 경험적으로 많이 알아낼 수 있다.
