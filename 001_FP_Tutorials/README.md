# link

- Blog정리중(260717)
  - https://younghakim7.github.io/blog/posts/260110_001fp_functional_programming/

- 외국 유튜브 영상
  - [영상모아보기 2022) Functional Programming | Missing CS Courses](https://youtube.com/playlist?list=PLA_-EWSPTJcu4i7RFCl_KeGrrz37C4_Oc&si=ZKhWyyLLwTzY13dN)

- C++좋은 책
  - [2018년도 책 Ivan Cukic | Functional Programming in C++: How to improve your C++ programs using functional techniques](https://www.amazon.com/Functional-Programming-programs-functional-techniques/dp/B0978262WN/)

  - [C++ 함수형 프로그래밍)C++과 함수형 프로그래밍 패러다임의 만남 PDF | 알렉산드루 볼보아카 저 최동훈 역 | 에이콘출판사 2024.12.02.](https://m.yes24.com/goods/detail/139862891)
    - 원서 : Hands-On Functional Programming with C++: An effective guide to writing accelerated functional code using C++17 and C++20

<hr />
 
# FP(Functional programming) 기본 개념
- ‘Functional programming is a style of programming that emphasizes the evaluation of expressions, rather than execution of commands. The expressions in these languages are formed by using functions to combine basic values. A functional language is a language that supports and encourages programming in a functional style.
—FAQ for comp.lang.functional’

- 함수형 프로그래밍은 명령 실행보다 표현식의 평가를 강조하는 프로그래밍 스타일입니다. 이러한 언어의 표현은 기본 값을 결합하기 위해 함수를 사용하여 형성됩니다. 함수형 언어는 함수형 스타일의 프로그래밍을 지원하고 장려하는 언어입니다.

—Comp.lang.functional에 대한 FAQ

- 다음에서 발췌
  -  Functional Programming in C++
    - Ivan Čukić

# 함수형 프로그래밍(Functional Programming)이란?

## Concept

> Avoids changing State and Mutable data

- 상태와 Data를 변경하는 것을 피하면서 프로그래밍하는 것입니다.
- 즉 대입문[assignment statements] 없이 프로그래밍하는 것입니다.

## 일급 시민(First-class citizens)
- 함수를 일급 시민으로 관리하겠다

### 일급 시민이 된다는 것은 무엇을 의미할까요?
- Argument로 전달할 수 있다는 의미. → 함수가 Argument로 전달될 수 있다.
- 함수의 Return값이 될 수 있다는 의미. → Return값이 함수가 될 수 있다.
- 값을 수정하기도, 값을 할당할 수도 있다는 의미. → 함수를 값처럼 할당하기도 수정도 할 수 있다.

### 일급 시민은 누가 있을까요?
- value
- type
- object
- entity

- https://nesoy.github.io/blog/Functional-Programming
