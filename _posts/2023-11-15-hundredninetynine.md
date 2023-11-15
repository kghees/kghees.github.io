---
layout: single
title:  "[BOJ/백준] 2346. 풍선 터뜨리기"
categories: CodingTest
tag: [deque, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2346>



  
  
# 과정

1. d의 덱에 enumerate를 써서 input받는다.  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/283122592-f7fe0339-cf89-4019-afda-4df75bf4d671.png)

2. 순서를 저장할 ans 리스트를 만들어준다.
3. x에는 순서 y에는 d에 있는 값을 pop해준다.
4. ans에 순서값을 넣어준다.
5. rotate는 원형 큐를 양수이면 오른쪽으로 돌려주고  
음수이면 왼쪽으로 돌려준다고 생각하면 된다.  
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/283124263-f3287a52-c77d-4033-80ff-18eac3ff4a8c.png)

6. ans 리스트를 출력해준다.

# 정답 코드

<script src="https://gist.github.com/kghees/24316d8ed037fd47f5f1fb531e95c411.js"></script>
    




