---
layout: post
comments: true
title:  "[책 리뷰] 밑바닥부터 시작하는 비트코인"
date:   2019-12-15
author: Cory
categories: Review
permalink : /daliy-life/review/programming-bitcoin
tags: review book
---

> 이 책의 리뷰는 한빛미디어 '나는 리뷰어다'로 부터 책을 지원받아 작성된 글입니다.

<img src="/assets/review/programming-bitcoin/programming-bitcoin-01.jpeg" alt="programming-bitcoin-01">

또 한번 역대급 책이 출간되었다는 소식을 듣고 이 책을 꼭 읽고 싶어서 지원하게 되었다. 비트코인 코어 개발자 __Jimmy Song__ 님의 책이었다. 기대를 많이 해서 그런지 정말 책을 받자마자 바로 정독을 시작했었다.

역시 책 내용은 최고라고 할 수 있을 것 같다. 일반적인 비트코인 책처럼 붕 뜬 느낌의 책이 아니라 __개발__ 을 하는 입장에서는 내부까지 이해할 수 있도록 쉽게 설명한 책이었다. 시중에 있는 비트코인 책 중에서는 [마스터링 비트코인](http://www.yes24.com/Product/goods/22357437) 이후로 맘에 드는 책이 하나도 없었는데, 이제 이 책을 추가하고 싶다. 

참고로 두 책을 비교하자면, __마스터링 비트코인__ 은 비트코인의 일반적인 개념들을 설명하고, 비트코인 클라이언트 사용법을 알려주어 실제 서비스에서 사용할 수 있는 방법을 알려주는 책이라면, __밑바닥부터 시작하는 비트코인__ 은 비트코인 그 자체에 대해서 세세하게 알려주는 책이라고 할 수 있을 것 같다. 만약 두 책을 모두 읽는다면 마스터링 비트코인을 읽은 후에 이 책을 읽는 것을 추천하고 싶다.

하지만 이 책의 경우 비트코인 코어 개발을 담은 만큼 수학적인 내용이 많이 들어가 있기 때문에, 비전공자(?) 입장에서는 이해하기 조금 어려울 수도 있다는 생각이 들었다. 그래도 비트코인을 활용한 서비스를 개발하는 사람이라면 이정도는 반드시 이해할 수 있어야만 한다고 생각한다. 그렇기 때문에 오늘 이후로 우리 회사 개발자의 필독서 중 하나로 추가할 예정이다.

위와 같은 점을 고려할 때 총 평은 __비트코인 개념을 가장 잘 알려주는 책__ 라고 말하고 싶다.

<img src="/assets/review/programming-bitcoin/programming-bitcoin-02.jpeg" alt="programming-bitcoin-02">

책은 비트코인, 블록체인 등에 입문 할 때 가장 힘들어하는 부분 중 하나인 __PKI__ 개념을 잡는 것부터 시작한다. 그런데 다른 책들과 달리 단순히 개념 설명만 하고 라이브러리를 사용하는 것이 아니라 정말로 __secp256k1__ 으로 시작해서 __비트코인 트랜잭션 서명__ 까지 라이브러리 없이 하나하나 개발해 나간다.그 이후 Scipt, 블록, 머클트리 등에 대해서 설명해 나간다. 마지막 장에는 최근(?) 진행한 segwit 에 대해서도 설명해 준다.

위 사진과 아래 사진을 보면 알 수 있지만 어려운 개념에 대해서는 그림(그래프) 와 함께 보여주고 코드도 깔끔하게 잘 정리되어 있어 보기도 편하다. 특히, 개념 설명을 해주고 이 개념이 어느 코드에 있는지 설명해주는 부분 때문에 처음 실습없이 읽어나갈 때에도 무리없이 진행 할 수 있었던 것 같다.

그래도 개발자라면 코드는 한번 돌려보는 것을 꼭 추천하고 싶다. 코드를 돌리면서 비트코인이 이런식으로 작동하는 구나를 간단하게 나마 느낄 수 있었기 때문이다. 물론 책에 나오는 연습문제를 풀어보려면 코드를 돌려볼 수 밖에 없다. (연습문제는 반드시 풀어 보도록 하자)

<img src="/assets/review/programming-bitcoin/programming-bitcoin-03.jpeg" alt="programming-bitcoin-03">

작성자의 경우 현재 블록체인 업계에 종사하기 때문에 더 관심이 있었을 지도 모른다. 그렇다고 하더라도 최근 읽은 블록체인 관련 책 중에 가장 흥미롭게 읽었던 것 같다. 한빝미디어의 베스트 셀러인 __밑바닥 부터 시작하는 딥러닝 1,2__ 의 이름을 가히 이을수 있을 책이라는 생각이 들었다.(작성자의 경우 저 두책도 모두 읽었었다.) 

또한 개인적인 생각에는 블록체인(비트코인) 업계 종사자가 아니라 일반 개발자들도 사서 읽어보면 평상시 사용하는 __Key 관련 내용__, __네트워크__ 등을 직접 코딩하면서 배울 수 있기 때문에 도움이 많이 될 것 같다.

그렇기 때문에 결론적으로 이 책을

- 1 비트코인 관련 종사자
- 2 신입 개발자

등에게 추천하고 싶다.
