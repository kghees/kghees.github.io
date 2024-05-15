---
layout: single
title:  "[BOJ/백준] 20055. 컨베이어 벨트 위의 로봇"
categories: CodingTest
tag: [구현,시뮬레이션, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/20055>



  
  
# 과정  
1. 컨베이어 벨트를 회전시켜야 하므로 어떻게 하면 될지 생각해본다.
2. deque를 쓰면 회전 시킬 때 제일 뒤에 있는 것을 앞으로 옮겨주고  
가장 뒤에를 뺴준다면 회전이 완성되므로 deque를 쓰기로 결정했다.  
(회전이라는 단어가 나온다면 deque 쓰는 것을 항상 고려해보자!!)  
3. robot과 belt queue를 각각 bool 형태와 int형태로 만들어서 belt 값을 입력 받아주고 robot은 처음에는 0개 이므로 모두 false를 넣어준다.  

4. turn부분에서 robot과 belt 부분에 대해서 회전을 진행시켜주고  
n번째(n-1)(인덱스를 0부터 시작함)가 항상 내리는 위치 이므로 항상 false를 해준다. 
5. move 부분에서는 n-1번째는 내리는 위치 이므로 그 전 인덱스부터 따져주면 된다.  
문제 조건에서 이동하려는 위치에는 로봇이 없어야 하고 현재 위치에는 로봇이 있어야 하며 이동하려는 위치의 벨트 내구도가 있어야 한다고 했으므로 if문으로 조건을 따져줘서 이행해준다.  
그 후 항상 내리는 위치는 빼주도록 한다.  
6. up 부분에서는 올리는 위치에 로봇을 올릴 조건(올리는 위치에 로봇이 없어야 하며 내구도가 남아 있어야함)을 따져 주고 로봇을 올려준다.  
7. check 부분에서는 내구도가 0인 곳의 수를 세서 k 이상이라면 false 그게 아니라면 true를 return 하도록 한다.  
8. 몇번째 단계에서 종료되었는지 출력한다. 




# 정답 코드
<script src="https://gist.github.com/kghees/cd9266d9d4dab3fdddf5df56f664d68d.js"></script>




