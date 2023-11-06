---
layout: single
title:  "[BOJ/백준] 10971. 외판원 순회2"
categories: CodingTest
tag: [backtraking, dfs, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/10971>



  
  
# 과정

1. 최소 값을 저장할 res를 1e9로 정의해준다.
2. 방문을 확인하기 위해 check 리스트를 만들어준다.
3. n번 반복에서 i를 방문확인하고 dfs()함수를 실행시켜주고
돌아오면 다른 경로도 확인해야하니 i도시에 대해 방문확인을 False해준다.
4. dfs(start,next,ans,cnt)  
start: 처음 시작한 도시 값 next: 다음 도착한 도시 값  
ans: 여행 비용   cnt: 들린 나라의 수
5. 만약 cnt가 n과 같다면 모두 들린 것이고 a[next][start](마지막 나라에서 처음 나라로 가는 비용)이 0이 아니라면 ans에 더해주고
res와 비교해 더 작은 값을 return해준다.
6. ans가 res보다 크면 더 이상 진행안해도 되니 바로 return해준다.
7. 방문하지 않았고 a[next][i] 값이 0이 아니라면 방문확인(True)해주고 다음 도시로 dfs를 실행시켜주고 돌아오면 다른 경로도 확인해야하니 i도시에 대해 방문확인을 False해준다.
8. res 값을 출력해준다.





# 정답 코드

<script src="https://gist.github.com/kghees/dc13551dd0a791182a739334ec169ee5.js"></script>
  
    




