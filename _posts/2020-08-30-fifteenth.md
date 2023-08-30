---
layout: single
title:  "[Algorithm] 스택(Stack) ,큐(Queue), 덱(Deque)"
categories: Algorithm
tag: [Concept]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---
이번 포스팅에서는 스택(Stack), 큐(Queue), 덱(Deque)에 대해서 알아보겠습니다.  



# 스택(Stack)이란?  

- 스택(Stack)은 "쌓다"라는 의미로, 데이터를 차곡차곡 쌓아 올린 형태의 자료구조이다.  
- 스택은 한쪽 끝에서만 자료를 넣고 뺄 수 있는 자료 구조이다.  
-> <span style="color:red">LIFO(Last In First Out)</span>  

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/264378923-4f20ae95-d545-42de-8124-ea8b6c41f6f0.png)
- stack에서의 Push, Pop은 시간 복잡도가 O(1)

# 큐(Queue)란?
- 큐(Queue)는 스택(Stack)과 다르게 한쪽 끝에서만 자료를 넣고 다른 한쪽 끝에서만 뺄 수 있는 자료구조이다.
-> <span style="color:red">FIFO(First In First Out)</span>  

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/264381422-8c100921-69f3-4f6a-870a-ed13fbd738a3.png)  

# 덱(Deque)란?  
- 덱(Deque)는 양 끝에서만 자료를 넣고 양 끝에서 뺄 수 있는 자료구조이다.
- 스택(Stack)과 큐(Queue)의 연산을 모두 지원한다.  

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/92205960/264383479-25225b78-c233-4e83-9ddc-3ce7a212cd3f.png)
