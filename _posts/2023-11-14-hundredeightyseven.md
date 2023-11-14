---
layout: single
title:  "[BOJ/백준] 18870. 좌표 압축"
categories: CodingTest
tag: [정렬, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/18870>



  
  
# 과정

1. 자신이 몇번째로 작은 지 알기 위해 arr에 중복이 제거된 오름차순 정렬 a를 넣어준다.
2. 시간복잡도를 O(1)로 하기 위해 dict 리스트에 각각의 arr[i]에 자신보다 작은 수의 개수를 넣어준다.
3. a에 해당 하는 i에 dic[i](자신에 맞는 작은수의 개수)를 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/333a770ada8d5ece53408c229204ed30.js"></script>
  
    




