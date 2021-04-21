# 슈퍼마켓 가격 계산! 

Link: [CodKata Step 1][http://codekata.com/kata/kata01-supermarket-pricing/]

이 카타는 우리가 참여했던 DFW 실무자 미팅 중 어떤 토론에서 발생했다.
문제의 도메인은 겉보기엔 간단한거 처럼 보였다 : 슈퍼마켓에서 상품을 계산하는 문제.

슈퍼마켓에서 몇몇 상품들은 매우 명료한 금액이었다. : 이 콩 통조림은 0.65 달러. 다른 것들은 보다 복잡한 가격들을 가지고 있었다.

예시 :
> 1달러의 3개를 구입가능 (만약 내가 4개 또는 5개를 산다면, 가격은 어떻게 되나 ?)
> $1.99/파운드 (4온스에 대한 코스트?)
> 2개를 사면 한개를 증정 ( 그럼 3번째 상품은 가격을 가지나 ?)
> 이 카타는 코딩을 필요로 하지않습니다.

연습은 이러한 (및 기타) 가격 책정 체계를 처리 할 수있을만큼 유연하고 동시에 일반적으로 사용할 수있는 돈과 가격을 나타내는 다양한 모델을 실험하는 것입니다.

이 연습은 동시에 일반적으로 사용할 수 있는 돈과 가격사이의 정책들의 대한 같은 시간과 많은 종류의 모델들로 실험합니다.
(계산할 때, 재고 관리에서, 주문 entry 등에서)
이슈들을 고려하는데 시간을 써야 합니다. :

* 잔돈이 있는가?

* 반올림이 발생할 수 있나?

* 가격 결정을 할때는 어떻게 결정 할 수 있는가 (그리고 이것이 필요한지)?

* 비용과 가격은 같은 클래스(등급) 인가 ?

* 만약 100개의 캔들의 선반이 "2개를 산다면 하나를 무료로 드려요" 라는 가격을 사용하고 있다면, 당신은 어떻게 재고의 측정할 것인가?

이것은 생각이 쏟아지는 카타이긴 하지만, 조심해야 합니다.

어떤 문제들은 첫번째 나타난 문제들보다 세밀해야 합니다.

나는 이것이 아마 몇 주 이상동안 대안들이 배출되고 논의 되어질 수 있다고 생각합니다.

### 목표
이 카타의 목표는 실험적 모델링의 느슨한 스타일을 연습하는 데 있습니다.
문제의 풀기 위해 핸들링하는 여러가지 방식들을 보세요.
각각의 다양한 장단점을 고려하십시오.

어떤 테크닉이 이 모델을 탐색하기에 베스트인지 ? 그것을 기록하기 위해?

어떻게 모델이 합리적인지를 검증 할 수 있을까?


### 원문 (링크이동도 하고 싶지 않은 당신을 위한)
This kata arose from some discussions we’ve been having at the DFW Practioners meetings. The problem domain is something seemingly simple: pricing goods at supermarkets.

Some things in supermarkets have simple prices: this can of beans costs $0.65. Other things have more complex prices. For example:

three for a dollar (so what’s the price if I buy 4, or 5?)
$1.99/pound (so what does 4 ounces cost?)
buy two, get one free (so does the third item have a price?)
This kata involves no coding. The exercise is to experiment with various models for representing money and prices that are flexible enough to deal with these (and other) pricing schemes, and at the same time are generally usable (at the checkout, for stock management, order entry, and so on). Spend time considering issues such as:

does fractional money exist?
when (if ever) does rounding take place?
how do you keep an audit trail of pricing decisions (and do you need to)?
are costs and prices the same class of thing?
if a shelf of 100 cans is priced using “buy two, get one free”, how do you value the stock?
This is an ideal shower-time kata, but be careful. Some of the problems are more subtle than they first appear. I suggest that it might take a couple of weeks worth of showers to exhaust the main alternatives.

Goal
The goal of this kata is to practice a looser style of experimental modelling. Look for as many different ways of handling the issues as possible. Consider the various tradeoffs of each. What techniques are best for exploring these models? For recording them? How can you validate a model is reasonable?

