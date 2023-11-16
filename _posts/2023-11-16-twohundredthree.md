---
layout: single
title:  "[SWEA] 1954. 달팽이 숫자"
categories: SWEA
tag: [python, D2]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=2&contestProbId=AV5PobmqAPoDFAUq&categoryId=AV5PobmqAPoDFAUq&categoryType=CODE&problemTitle=&orderBy=RECOMMEND_COUNT&selectCodeLang=PYTHON&select-1=2&pageSize=10&pageIndex=1>




  
  
# 과정

1. 숫자를 채워넣을 리스트 a를 만들어주고 a리스트의 첫번째에 1을 넣어준다.
2. dfs(idx,cnt,x,y) idx:방향벡터 번호, cnt:현재 넣을 숫자
x,y: a리스트 인덱스를 실행시켜준다.
3. 방향벡터 dx,dy를 달팽이 숫자의 방향에 맞게 만들어준다.
4. dfs()에서 cnt가 n*n보다 커지면 숫자 범위를 넘어갔으므로 return해준다.
5. nx,ny에 x,y + 방향벡터[idx]를 더해준다.
6. nx,ny가 범위를 벗어나지 않고 a[nx][ny] 값이 0이라면  
a[nx][ny]에 cnt 값을 넣고 dfs()에 idx는 유지 cnt에는 1을 더하고 x,y대신 바뀐 nx,ny값을 넣어준다.
7. 범위를 벗어났으면 방향벡터 값을 갱신해서 dfs()해준다.
8. 테스트 케이스 번호와 a리스트 값을 출력해준다.


# 정답 코드
<script src="https://gist.github.com/kghees/3d7cba83d12c308fad2382b28faf9734.js"></script>
  



