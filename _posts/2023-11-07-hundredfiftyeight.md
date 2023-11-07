---
layout: single
title:  "[Algorithm] 후위 표기법(Postfix notation) "
categories: Concept
tag: [Algorithm]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---
이번 포스팅에서는 시간 복잡도에 대해서 알아보겠습니다.  

  
# 1. 후위 표기법이란?(Postfix notation)
## <span style="color:red">***정의***</span>  
: 후위 표기법(역폴란드 표기법, Reverse Polish Notation)은 연산자를 피연산자 뒤에 쓰는 연산 표기법이다.   
예를 들어, 3 + 5 × 2 우리가 사용하는 방법을 중위 표기법이라고 하며, 이를 후위 표기법으로 바꾸며 아래와 같다.

3 5 2 × +

후위 표기법으로 바꾸는 방법을 알려면, 먼저 후위 표기법의 수식을 계산하는 방법을 이해해야 한다.

# 2. 후위 표기법 수식을 계산하는 방법
1. 숫자는 스택에 넣는다. stack = [3,5,2]
2. 연산자가 나오면 스택에서 숫자 2개를 꺼내서 계산한다.
3. 두개의 결과 값을 스택에 저장한다.
4. 다음 연산자가 있으면 2번을 반복한다.
- <span style="color:red">연산자 순서</span> 를 꼭 따져주어야 한다.


# 3. 후위 표기법으로 바꾸는 방법
1. 숫자를 만나면 출력
2. 연산자를 만나면  
- 스택에 연산자가 있는지 확인  
- 스택의 마지막 연산자가 현재 연산자보다 우선순위가 높으면 빼서 출력
3. 현재 연산자를 스택에 넣는다.
4. 스택이 빌 떄 까지 pop하여 출력한다.

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/280924774-5647f7ff-7594-4ce7-89ee-8f2af66a2156.png)
