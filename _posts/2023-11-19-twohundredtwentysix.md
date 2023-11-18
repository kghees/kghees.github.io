---
layout: single
title:  "[BOJ/백준] 14225. 부분 수열의 합"
categories: CodingTest
tag: [브루트포스, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/14225>



  
  
# 과정
## 1
1. a리스트를 오름차순 정렬해준다.  
없는 수를 찾기 위한 x를 0으로 정의해준다.
2. 만약 x+1보다 i가 크다면 x+1인 수가 합으로 만들 수 없다는 뜻이므로 break해주고  
x+1보다 i가 작거나 같으면 만들 수 있는 수 이므로 x에 i를 더해준다.
3. x+1을 출력해준다.  
  
## 2
1. 수열의 합이 있는지 저장하기 위한 check리스트를 만들어준다.
2. dfs()함수에서 cnt와 n이 같다면 모든 합을 구한 것이므로 return해준다.
3. ans에 a에서cnt번째의 값을 더해주고 check리스트에 ans 값에 대해 1을 해준다.
4. dfs()함수에서 더한 값에 대해도 실행시키고 원래의 값에 다른 값을 더해 볼 수도 있으니 a[cnt] 값을 빼서도 실행시킨다.
5. check리스트에서 0이라면 수열의 합으로 만들 수 없는 수 이므로
출력해준다.


# 정답 코드
## 1
<script src="https://gist.github.com/kghees/0d6abbb4d10fa5a859b61c504af11538.js"></script>  
  
## 2
<script src="https://gist.github.com/kghees/ba08bf2c6f326d98c3470466cef6f759.js"></script>




