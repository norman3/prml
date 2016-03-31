---
layout: page
title: Sample 페이지
---

이 페이지는 샘플 페이지입니다.

{% comment %}
라인 삽입
{% endcomment %}

- - -

{% comment %}
이텔릭체
{% endcomment %}

_word_

*word*

{% comment %}
볼드체 삽입
{% endcomment %}
**word**

{% comment %}
URL 삽입
{% endcomment %}

http://exaple.com

[Link](http://example.com)

[Link](http://example.com){:target="_blank"}

{% comment %}
취소선 (스트라이크)
{% endcomment %}

~~Mistaken text.~~

{% comment %}
코드 삽입
{% endcomment %}

``` javascript
function test() {
  console.log("Hello, world.");
}
```

``` cpp
#include <iostream>

int main() {
  std::cout << "Hello world." << std::endl;
  return 0;
}
```

{% comment %}
테이블 삽입
{% endcomment %}

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

{% comment %}
문장 내 코드 삽입
{% endcomment %}

문장내 `code` 삽입

{% comment %}
ul, li 삽입
{% endcomment %}

- Item 1
    - item 1
    - item 2
- Item 2
    - item 1
    - item 2

{% comment %}
타이틀 삽입
{% endcomment %}

# heading
## heading
### heading


{% comment %}
인용문 삽입
{% endcomment %}

> blockquote
> bq 1
> bq 2


{% comment %}
이미지 삽입
{% endcomment %}

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")


{% comment %}
Latex 삽입
{% endcomment %}

문장 중간에 \\(\mu : \mathcal{S} \rightarrow \mathbb{R} \\) Latex 삽입.


measure \\( \mu : \mathcal{S} \rightarrow \mathbb{R} \\)

1. $$ \mu(\phi) = 0 $$
2. $$ \bigcup_n{A_n} = A \wedge \forall n, m : A_n \cap A_m = \phi \rightarrow \sum_n{\mu(A_n)} = \mu(A) $$

outer measure \\( \mu^* : \mathcal{P}(X) \rightarrow \mathbb{R} \\)

$$ \mu^*(A) = \inf \left\lbrace \sum_n{A_n} : A \subset \bigcup_n{A_n}, \forall n A_n \in \mathcal{S} \right\rbrace $$
