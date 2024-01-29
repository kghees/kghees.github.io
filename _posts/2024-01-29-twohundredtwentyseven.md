---
layout: single
title:  "[SWEA] 2005 파스칼의 삼각형"
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
1. n의 범위가 1~10이므로 arr배열을 11크기로 초기화 해준다.
2. 첫번째 줄은 항상 1이라고 했으므로 arr[0][0] = 1로 초기화 해준다.
3. 규칙을 찾아보면 다음 아래와 같다.  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/300463991-b0394e65-e748-40da-a42e-f530ab337262.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240129%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240129T130158Z&X-Amz-Expires=300&X-Amz-Signature=5c15761c38d30f7103d29bca8c384bb2b548f15471c40b6f613b0b764e04ee68&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=659027418)
4. 범위에 맞게 출력해주면 된다.
  



# 정답 코드
<script src="https://gist.github.com/kghees/02d99f4fd12476df1894554fe472915e.js"></script>
  




