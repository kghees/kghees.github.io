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
## 1
1. n의 범위가 1~10이므로 arr배열을 11크기로 초기화 해준다.
2. 첫번째 줄은 항상 1이라고 했으므로 arr[0][0] = 1로 초기화 해준다.
3. 규칙을 찾아보면 다음 아래와 같다.  
![image](https://github.com/kghees/Coding-Test/assets/92205960/11e4568d-8820-4538-b8a5-10efe1c79e0e)
4. 범위에 맞게 출력해주면 된다.
  



# 정답 코드
<script src="https://gist.github.com/kghees/02d99f4fd12476df1894554fe472915e.js"></script>
  




