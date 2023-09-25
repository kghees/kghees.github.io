---
layout: single
title:  "[BOJ/백준] 실버1 1309번 동물원"
categories: CodingTest
tag: [Algorithm, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/1309>


# 문제
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/270385370-90ee6218-134e-4c03-8c22-885559cc5768.png)


## 입력
첫째 줄에 우리의 크기 N(1≤N≤100,000)이 주어진다.


## 출력
첫째 줄에 사자를 배치하는 경우의 수를 9901로 나눈 나머지를 출력하여라.
  
  
# 과정
점화식을 먼저 세우게 되면  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/270386545-913e9726-58e0-4804-b9f4-b75ecbcbf5fb.png)  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/270388024-ef873ab3-fb1f-4b10-bd54-cdb29888c4e4.png)  
  

# 정답 코드
<script src="https://gist.github.com/kghees/33753471632580841df98ab444f589a6.js"></script>
  
    

# 시행 착오
처음에 배치 안하는 경우를 생각하지 못하고 왼쪽과 오른쪽에 배치 하는경우만  
생각해서 해보니 틀려서 다시 곰곰히 생각해보니 배치 안하는 경우도 떠올렸다!

# 후기
DP에 적응하고 있는것 같아서 뿌듯하다!!
