---
layout: single
title:  "[BOJ/백준] 12018. Yonsei TOTO"
categories: CodingTest
tag: [Greedy, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/12018>



  
  
# 과정

1. 수강신청할 수 있는 과목의 수를 저장할 res를 만들어준다.
2. 각 과목마다 필요한 마일리지를 저장할 ans리스트를 만들어준다.
3. 과목을 입력받고 내림차순 정렬을 해준다.
4. 수강인원이 수강가능 인원보다 크거나 같으면 ans에 이 과목을 수강하기 위해 필요한 마일리지를 추가해준다.
5. 수강인원이 수강가능 인원보다 작으면 1마일리지만 투자하면 되므로 ans에 1을 추가해준다.
6. ans 리스트를 오름차순 정렬해준다.
7. ans에 있는 i에서 마일리지(m)가 i보다 크거나 같으면 수강할 수 있으므로 res에 1을 더해주고 마일리지(m)에서 i만큼 뺴준다.
8. res를 출력한다.



# 정답 코드

<script src="https://gist.github.com/kghees/171cb342c19eec5b649bbcab8af7fef4.js"></script>
  
    




