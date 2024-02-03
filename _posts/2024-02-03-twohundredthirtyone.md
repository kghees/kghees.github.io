---
layout: single
title:  "[백준] 11650. 좌표 정렬하기"
categories: CodingTest
tag: [sort , c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/11650>



  
  
# 과정
## 1 구조체
1. 좌표를 정렬하기 위한 변수를 담을 구조체 coordinate(좌표)를 만들어준다.
2. x좌표 y좌표를 비교하기 위한 cmp 함수를 만들어준다.
3. x좌표가 같다면 b의 y좌표가 더 뒤로 가도록 해주고  
   x좌표가 다르다면 b의 x좌표가 더 뒤로 가도록 해준다.
4. 출력에 맞게 출력해준다.
  
## 2 벡터
1. vector에서 쌍으로 받기 위해 pair를 써주어 arr을 만들어준다.
2. sort함수를 쓰면 vector의 first를 기준으로 정렬해주고 first가 같다면  
second를 기준으로 오름차순 정렬해준다.
3. 출력에 맞게 출력해준다.


# 정답 코드
## 1 구조체
<script src="https://gist.github.com/kghees/ac7209e6d9252705d5eb32380ebfa58e.js"></script>
  
## 2 벡터
<script src="https://gist.github.com/kghees/a2ca1622a423cca6890de1ea3f1089ab.js"></script>




