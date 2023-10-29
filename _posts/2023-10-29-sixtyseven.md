---
layout: single
title:  "[SWEA] 5515. 2016년 요일 맞추기"
categories: SWEA
tag: [python, D3]
toc: true
author_profile: false
sidebar:
    nav: "counts"
---

# 출처
<https://swexpertacademy.com/main/code/problem/problemDetail.do?problemLevel=3&contestProbId=AWWOwecaFrIDFAV4&categoryId=AWWOwecaFrIDFAV4&categoryType=CODE&problemTitle=&orderBy=PASS_RATE&selectCodeLang=PYTHON&select-1=3&pageSize=10&pageIndex=5>

  
  
# 과정
1. 1월부터 12월의 일수를 저장하기위한 month를 저장
2. 1월부터 12월 까지 일수에 따라 month[i]안에 공간을 저장
3. 2016년 1월 1일은 금요일이기 때문에 x를 4로 저장
4. 1월부터 12월까지 일마다 요일을 x를 기반으로 % 7해서 각각 저장
5. 테스트케이스 번호와 m,d에 해당하는 요일 출력






# 정답 코드
<script src="https://gist.github.com/kghees/f2e075d39e7de94fccf375b5e58136ef.js"></script>