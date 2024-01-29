---
layout: single
title:  "SWEA 2005 파스칼의 삼각형"
categories: CodingTest
tag: [D2, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/14225>



  
  
# 과정
## 1
1. n의 범위가 1~10이므로 arr배열을 11크기로 초기화 해준다.

2. 첫번째 줄은 항상 1이라고 했으므로 arr[0][0] = 1로 초기화 해준다.
3. 규칙을 찾아보면 다음 아래와 같다.  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/300457703-293fe06e-14bd-4436-ae30-ce20352278a1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240129%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240129T124755Z&X-Amz-Expires=300&X-Amz-Signature=68fa62d827c1dc57265b26502470cdb23264cf448cf4b0c8668caefc08298bf7&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=659027418)
4. 범위에 맞게 출력해주면 된다.
  



# 정답 코드
## 1
<script src="https://gist.github.com/kghees/02d99f4fd12476df1894554fe472915e.js"></script>
  




