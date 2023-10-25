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
점화식을 먼저 세워야한다.  
D[i] = A[1]...A[i]까지 수열 중, A[i]를 마지막으로 하는 가장 긴 증가하는 수열의 길이 라고 세웠다.
A[j]라고 두고 A[i]전까지의 증가하는 수열의 수 중 마지막 수 라고 두자 A[j] < A[i]  
예를 들어 A = [10,20,10,30,20] 이라고 하자!  

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266356485-4c746330-c9bd-4223-b74f-5b0ca912ac7f.png)  

이것을 표를 구성해서 그림으로 풀어지는 순서를 보여보겠습니다.  

1. ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266358614-5f6c27dd-4895-4101-9abe-541c4b4a2c01.png)  
2. ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266359424-472d93d0-9888-4b94-93ec-43797154254c.png)  
3. ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266359701-94d06596-135e-4995-8144-7e242c6e5c6d.png)  
4. ![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/266360398-c1a4f274-ed40-439e-bdc1-78f5da5a9383.png)  
  
  
# 정답 코드
<script src="https://gist.github.com/kghees/7b66bedf908b6196b5eb084fa1375f17.js"></script>
  
    

# 시행 착오
점화식의 정의는 잘 세웠지만 d[i-1] 즉 바로 앞에 값에만 집중해서 풀다가
그 앞에 수들과 비교하는 방법을 생각을 못했었다.   
하지만 표를 그려서 직접해보니 푸는 방법이 보이기 시작하였다.

# 후기
값들을 넓게넓게 쓸 수 있는 수들을 잘 봐보자!!!!!


