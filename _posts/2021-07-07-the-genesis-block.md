---
layout: post
title:  "최초의 비트코인 블록, Genesis 제네시스블록"
date:   2021-07-07 16:35:17 -0400
categories: bitcoin, reference
tags: block
---

2009년 1월 3일 미국동부시간 오후 1시 15분, 비트코인의 첫번째 블록이 생성됩니다. 블록안에는 생성시간, 해쉬, 크기, 비트코인 거래 기록이 담겨있고 아울러 사토시나카모토가 심은 메세지 또한 블록안에 영원히 담겨져 출력되게 됩니다.  비트코인의 첫번째로 생성된 블록, 그 후로 생성되는 모든 거래의 기반으로 깔리게 될 블록, Block0 이라고 불리우는 제네시스블록(Genesis Block)이 생성된 것입니다.  Genesis란 창세, 기원등의 시초의 의미를 담고 있으며 Block 블록은 블록체인기술에서 기록이 담긴 각각의 장부라고 볼수 있겠습니다.

<div class="tweet">

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">The <a href="https://twitter.com/hashtag/Bitcoin?src=hash&amp;ref_src=twsrc%5Etfw">#Bitcoin</a> Genesis Block being mined<br><br> <a href="https://t.co/8L2g8xGrtW">pic.twitter.com/8L2g8xGrtW</a></p>&mdash; Documenting Bitcoin 📄 (@DocumentingBTC) <a href="https://twitter.com/DocumentingBTC/status/1412749950530826243?ref_src=twsrc%5Etfw">July 7, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
첫번째 블록이 채굴되는 영상
</div>

### Coinbase
지금은 <code>$COIN</code> 코인베이스 회사가 더욱 유명하지만 사실 coinbase는 블록의 첫번째 거래를 일컫는 것으로 블록을 생성한 채굴자가 첫번째 거래로 채굴의 보상을 자신의 주소로 보내는 기록과 수수료등이 포함됩니다.  사토시나카모토는 제네시스블록의 coinbase에 첫 50비트코인을 보내는 정보를 넣으며 이하의 메세지를 첨부하는데, 바로 블록이 탄생한 날과 동일한 날에 발행된 영국의 The Times 신문 1면의 해드라인입니다.

![](https://www.thetimes03jan2009.com/wp-content/uploads/2015/03/genesis-block-newspaper-bitcoin.jpg)

>"Chancellor on brink of second bailout for banks"<br>
>"은행들의 두번째 구제금융을 앞두고 있는 (영국)재무장관"

당시 무분별한 금융업계의 사업들로 위기가 다가오자 국가에서 구제금으로 문제를 해결해주고자 하는 소식의 해드라인을 첨부하며, 사토시나카모토는 중앙화 된 금융시스탬에서 벗어나야 하는 비트코인의 필연적 존재목적을 호소하고 싶었는지 모르겠습니다.

![](http://wiki.hash.kr/images/thumb/4/46/%EB%B9%84%ED%8A%B8%EC%BD%94%EC%9D%B8_%EC%A0%9C%EB%84%A4%EC%8B%9C%EC%8A%A4_%EB%B8%94%EB%A1%9D.png/350px-%EB%B9%84%ED%8A%B8%EC%BD%94%EC%9D%B8_%EC%A0%9C%EB%84%A4%EC%8B%9C%EC%8A%A4_%EB%B8%94%EB%A1%9D.png)

### 신문
해당 제목을 실은 1월 3일자 더타임즈 신문은 시간이 지날수록 비트코인의 인기와 더불어 희소가치 또한 높아져서 현재 검증되어 남아있는 8부는 <https://www.thetimes03jan2009.com/> 을 통하여 소유자로부터 직접 거래가 가능한데, 이 글이 발행되는 2021년 가격은 최소 $250,000, 최대 $1,300,000 입니다.  워낙 코인계에선 중요한 역사적 인쇄물이기에 복사본들도 거래가 되고 있으며 위의 웹사이트에서는 검증서비스까지 제공하고 있습니다.

![증서와 신문이 옆에 놓인 사진](https://www.thetimes03jan2009.com/wp-content/uploads/2015/03/the-times-jan-03-2009.jpg)
검증후 인증서.


### 최초의 비트코인
최초의 비트코인은 제네시스블록의 생성과 함께 보상으로 50개의 비트코인이 <code>1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa</code> 이곳으로 보내졌으며 의도적이었는지는 모르겠으나 코드상 이 50 비트코인을 글로벌 거래내역에 포함되지 않으면서 결과적으론 <code>1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa</code> 안에 영원히 갇힌 비트코인이 되었습니다. 물론 사토시나카모토 외엔 지갑의 접근조차 불가능 하겠지만 말입니다.


### 제네시스와 두번째 블록과의 빈 시간
비트코인의 블록생성시간은 평균 10분으로 지정되어 있지만 제네시스블록 생성 후 두번째 블록이 생성되기 전까지는 5일 9시간이라는 공간이 있습니다. 5일 9시간 동안 어떤일이 있었던 걸까요?

![](https://i.ibb.co/gMCNx9B/1232355.png)

이에 관해 몇가지 가설들이 있습니다.[^1]
* 해쉬가 너무 낮아서 블록 1을 생성하는데 5일이 걸렸을거라는 가설
* 사토시나카모토가 작업을 하던중 1/3일자 신문제목이 너무 맘에 들어서 제네시스블록을 바꾸었을 가설
* 제네시스블록은 1/3에 완료되었으나 그 후 5일간 여러 테스팅을 마친 후 제네시스블록만 유지하고 그 외는 삭제하였을거라는 가설

어떠한 이유에서 였을지 어떠한 방식으로 왜 제네시스블록에 1월3일의 헤드라인이 첨부되었어야 하는 그 날짜인지 공백기간은 왜 생겼는지 알 수 없습니다.


### Hash
제네시스블록의 해쉬는 <code>000000000019d6689c085ae165831e934ff763ae46a2a6c172b3f1b60a8ce26f</code>
로 초창기 생성된 블록보다 0이 두개가 더 붙어있습니다.

### 기타
제네시스블락 외에도 채굴자들이 특별 메세지를 여기 저기 넣어 놓았는데 [블록 666,666](https://blockchair.com/bitcoin/block/629999)에는 ""선함으로 악을 이기라""는 성경구절도 볼 수 있고,
![](https://i.ibb.co/ZW7w8j3/144be65a-3eae-4785-a44c-a5224f1d1eb5.jpg)



최근 엘살바도르에서 비트코인의 법정화폐소식의 신문 해드라인을 넣기도 하였습니다.
![](https://i.ibb.co/mNJFnj6/234234123.png)

[^1]: https://en.bitcoin.it/wiki/Genesis_block
