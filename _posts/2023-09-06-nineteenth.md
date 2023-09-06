---
layout: single
title:  "[BOJ/백준] 실버2 11053번 가장 긴 증가하는 부분 수열"
categories: CodingTest
tag: [Algorithm, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/11053>


# 문제
수열 A가 주어졌을 때, 가장 긴 증가하는 부분 수열을 구하는 프로그램을 작성하시오.

예를 들어, 수열 A = {10, 20, 10, 30, 20, 50} 인 경우에 가장 긴 증가하는 부분 수열은   
A = {10, 20, 10, 30, 20, 50} 이고, 길이는 4이다.


## 입력
첫째 줄에 수열 A의 크기 N (1 ≤ N ≤ 1,000)이 주어진다.

둘째 줄에는 수열 A를 이루고 있는 Ai가 주어진다. (1 ≤ Ai ≤ 1,000)


## 출력
첫째 줄에 수열 A의 가장 긴 증가하는 부분 수열의 길이를 출력한다.
  
  
# 과정

# 정답 코드
<script src="https://gist.github.com/kghees/7b66bedf908b6196b5eb084fa1375f17.js"></script>
  
    

# 시행 착오
점화식의 정의는 잘 세웠지만 d[i-1] 즉 바로 앞에 값에만 집중해서 풀다가
그 앞에 수들과 비교하는 방법을 생각을 못했었다.   
하지만 표를 그려서 직접해보니 푸는 방법이 보이기 시작하였다.

# 후기
값들을 넓게넓게 쓸 수 있는 수들을 잘 봐보자!!!!!


