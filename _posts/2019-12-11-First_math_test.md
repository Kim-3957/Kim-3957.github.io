---
title: "Jekyll Github 블로그에 MathJax로 수학식 표시하기"
excerpt: "설정 순서등등"
tags:
- Blog
- MathJax
- Jekyll
- LaTeX
use_math: true
--------------

# 수학식 표기의 예

밑에 있는건 예시이다.  
This formula $f(x) = x^2$ is an example.  
> $f(x) = x^2$

Latex를 이용하기 때문에 평범한 Lates의 사용법이랑 작성법은 다른것이 없다.  

# Jekyll Github 블로그에 MathJax로 수학식 표시하기
출처: [Minki Kim](https://mkkim85.github.io/blog-apply-mathjax-to-jekyll-and-github-pages/)
1. _config.yml 파일 수정
2. mathjax_support.html 파일 생성
3. _layouts/default.html 파일 수정
4. YAML front-matter 설정

이러면 준비가 끝난다.  
물론 라텍스를 모른다면 공부를..
이하는 예시.

$$
a + b = c
$$

끝
