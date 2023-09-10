---
layout: single
title:  "[BOJ/백준] 실버2 1912번 연속합"
categories: CodingTest
tag: [Algorithm, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1912>


# 문제
n개의 정수로 이루어진 임의의 수열이 주어진다. 우리는 이 중 연속된 몇 개의 수를 선택해서 구할 수 있는 합 중 가장 큰 합을 구하려고 한다.   
단, 수는 한 개 이상 선택해야 한다.

예를 들어서 10, -4, 3, 1, 5, 6, -35, 12, 21, -1 이라는 수열이 주어졌다고 하자. 여기서 정답은 12+21인 33이 정답이 된다.


## 입력
첫째 줄에 정수 n(1 ≤ n ≤ 100,000)이 주어지고 둘째 줄에는 n개의 정수로 이루어진 수열이 주어진다.   
수는 -1,000보다 크거나 같고, 1,000보다 작거나 같은 정수이다.


## 출력
첫째 줄에 답을 출력한다.
  
  
# 과정
일단 점화식을  
D[i] = i번째 수로 끝나는 가장 큰 연속합이라고 세웠다.  
이러면 2가지 경우가 나오는데  
1. D[i-1]번째가 포함된 연속합
2. A[i]부터 시작되는 새로운 연속합
그래서 D[i] = max(D[i-1]+A[i],A[i])라고 점화식이 나왔다!  
  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266824191-e1b95c2c-ae97-46c7-bee9-a750bf2bc508.png)  
  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266824317-7a279c18-66c1-4ffb-968e-324f1d9121b6.png)

# 정답 코드
<script src="https://gist.github.com/kghees/167543f914e076f3fcde4c9067b090a9.js"></script>
  
    

# 시행 착오
전에 푼 가장 증가,감소하는 수열은 수열의 길이를 구하는 것이었지만  
이 문제는 값을 구하는 문제라 어떻게 해야할까 생각을 좀 했었던 거 같다.  
그냥 길이에서 값으로만 바꿔주면 된다는 생각으로 해보니 해결되었다!

# 후기
DP 좀 하는것 같기도,,,?
