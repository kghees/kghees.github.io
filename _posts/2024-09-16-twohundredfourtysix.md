---
layout: single
title:  "C# 배열 합치기"
categories: Concept
tag: [C#]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 1.Concat  
- arr1.Concat(arr2)는 arr1 배열과 arr2 배열을 하나로 병합하고 enumerable 객체로 return합니다.  
ToArray()로 Eumerable을 배열로 변환할 수 있다.  
- 합쳐진 요소들이 Enumerable로 return되기 때문에, 원본배열의 데이터가 변경되지 않는다.  
<script src="https://gist.github.com/kghees/1e5d5b7b12294601fe314cb674542110.js"></script>  
  
    
# 2.List를 이용  
- 배열의 크기는 동적으로 변경이 안되기 때문에, List 객체를 만들고 두 배열의 요소들을 List에 추가한 뒤에 List를 배열로 변경  
<script src="https://gist.github.com/kghees/4983ef92f2ae98acc39ce7725b751a47.js"></script>
  
