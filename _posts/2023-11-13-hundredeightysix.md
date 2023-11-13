---
layout: single
title:  "[BOJ/백준] 2504. 괄호의 값"
categories: CodingTest
tag: [stack, 구현, python]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://www.acmicpc.net/problem/2504>



  
  
# 과정

1. 괄호를 넣고 비교할 stack 리스트를 만들어준다.
2. 결과 값을 저장할 res를 0으로 정의하고 괄호의 값들을 곱하고 res에 더해줄 x를 1로 정의해준다.
![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/282460032-96d69528-2717-4268-866b-0ed913d5b6c5.png)
원래는 2(2+3*3) + 3*2 이지만  
그림처럼 바꾸어주면 4+18+6으로 바꾸어서 풀어주는게 핵심이다!!
3. s[i]가 '('이라면 x에 2를 곱해주고 '['이라면 x에 3을 곱해주고 stack에 s[i]를 추가해준다.
4. s[i]가 ')'일때 stack이 비었거나 stack의 마지막이 '('이 아니라면 괄호가 성립하지 않으므로 res를 0으로 하고 break해준다.  
그 전 괄호가 '('라면 res에 현재 x값을 더해준다.  
x를 2로 나누어주고 stack의 마지막 괄호를 pop해준다.
5. s[i]가 ']'일때 stack이 비었거나 stack의 마지막이 '['이 아니라면 괄호가 성립하지 않으므로 res를 0으로 하고 break해준다.  
그 전 괄호가 '['라면 res에 현재 x값을 더해준다.  
x를 3으로 나누어주고 stack의 마지막 괄호를 pop해준다.
6. 스택에 괄호가 남아있다면 성립하지 않는 괄호 이므로 0을 출력한다.  
그게 아니라면 성립하므로 res값을 출력해준다.



# 정답 코드

<script src="https://gist.github.com/kghees/a2cc4f9eb61d156edac803ef51d595ef.js"></script>
  
    




