---
layout: single
title:  "[BOJ/백준] 2785. 체인"
categories: CodingTest
tag: [Greedy, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2785>



  
  
# 과정

1. 체인의 길이 리스트 a를 오름차순 정렬해준다.
2. 고리의 수를 세기위한 res를 만들어준다.
3. 체인의 개수가 1보다 작거나 같으면 고리가 필요 없으므로 break해준다.
4. 체인의 길이가 체인의 개수 - 1 보다 크거나 같으면  
하나씩 이어 붙이는게 효율적이므로 res에 n-1을 더해준다.
5. 체인의 길이가 1이라면 3개짜리 -> 1개짜리로 바꿀 수 있으므로
n(체인의 개수)에서 2를 빼주고 res(고리의 개수)에 1을 더해준다.
6. 체인에서 고리를 하나때서 이으면 2개의 고리를 1개로 만들수 있으므로 n의 값은 -1, res는 +1이 된다.  
이 체인의 고리들을 다 써써 없어지면 2개짜리 - > 1개짜리로 변하므로
n-=2, res += 1을 해준다.
7. res 값을 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/9d76c1b43cae35d4124cfbb12919d709.js"></script>
  
    




