---
layout: single
title:  "[BOJ/백준] 9996. 한국이 그리울 땐 서버에 접속하지"
categories: CodingTest
tag: [문자열, c++]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/9996>



  
  
# 과정
1. pos에 별표의 위치 인덱스를  find함수를 써서 찾아준다.
2. pre에는 별표 앞부분 문자열을 suf에는 별표 뒷부분 문자열을 저장해준다.
3. pre + suf사이즈가 a의 사이즈보다 크면 NE를 출력해준다.  
(반례로 ab*ab일 때 ab가 들어오면 맞다고 출력됨)
4. pre와 a의 앞부분이 같고 suf와 a의 뒷부분이 같다면 DA출력해주고  
그게 아니라면 NE를 출력해준다.




# 정답 코드
<script src="https://gist.github.com/kghees/b9e98193a9bc8a0331a10fc18863ee32.js"></script>




