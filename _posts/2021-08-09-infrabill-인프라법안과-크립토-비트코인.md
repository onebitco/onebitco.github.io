---
layout: post
title:  "인프라 법안과 비트코인 및 크립토 브로커 정의"
date:   2021-08-09 19:02:10 -0400
categories: bitcoin
tags: bill
---

인프라법안의 자금충당 목적으로 크립토시장으로 눈을 돌리면서 브로커의 정의와 채굴자의 문자적 정의에 대한 여러 토론들이 오가며 수정안이 길어졌습니다.  이곳에 지난 일주일간의 트윗을 나누고 몇가지 생각들을 추가하여 정리했습니다.

앞으로 하원에서 부터 여러 수정안들을 트윗에도 올리겠지만 이곳에 정리합니다.

요약.
- 브로커의 정의가 느슨하게 잡힘. 채굴자도 사용자 정보를 제출해야하는 상황
- 수정안1. 채굴자, 개발자, 지갑판매자는 제외한다 추가
- 수정안2. 작업증명 채굴자, 지갑판매자 제외.  개발자언급 x
- 수정안3. Pow, Pos 채굴자 제외, 지갑판매자 제외.  개발자언급 x
- 수정안4. pow, pos 언급을 뺌. 모든 채굴자 제외.
- 수정안5. 모든 체굴자 제외, 개발자 제외, 지갑판매자 제외
- 투표전날 수정안 채택에 대한 투표를 진행. 100명 모두 동의 필요.
- 알라바마 상원의원 이의 제기. 수정안 부결.
- 하원으로 갈 예정.


### 8/1 일요일
5000장 정도의 미국 인프라법안이 제출됬고 이번주에 법안수정이 들어갑니다. 여기서 비트코인을 포함한 암호화폐 커뮤니티에 영향이 가는 부분이 갑자기 추가되어 나름 친 비트 의원들이 다급한 몇 일을 보낸듯 합니다.

암호화폐와 연관된 법안의 핵심은,
암호화폐 거래에 참여하는 ‘브로커’는 국세청의 보고 요건을 따라야함과 더불어 사용자의 정보까지 넘겨야 하여 이를 통해 인프라법안 중 280억달러를 조달한다는 내용입니다.

1️⃣ 브로커의 정의를 너무 느슨하게 잡은 상태.
초안에는 채굴자 PoW&PoS, 소프트웨어개발자, 노드보유자까지 포함하였으나 지난 일요일 브로커 정의가 좀 더 개선되어, “타인을 대신하여 디지털 자산의 양도를 유발하는 서비스를 정기적으로 제공할 책임이 있는 사람” 이라고 수정되었습니다.

중요한 문구는 “effectuate transfers” ‘이전을 유발하는’이라는 부분인데 이 법안을 도운 Portman은 “개인 보유자들이나 브로커가 아닌 이들, 즉 채굴자나 개발자등을 포함하는 것이 아니다” 라고 밝혔지만 그것이 분명하다면 왜 법안에 더 명확한 표기가 되지 않고 있는가에 대한 의문이 남습니다

2️⃣채굴자는 브로커가 X
암호화폐 채굴자는 보안과 연관되어 채굴을 통한 보상을 받는 서비스 입니다. 특성상 익명성과 permissionless 비허가형이 동반 될 수 밖에 없기에 거래자들 등록이 불가능하며 중국의 통제와 같은 결과로써 채굴자들을 미국 밖으로 몰아내게 될것이다 우려하고 있습니다.

3️⃣감시?
초안은 “암호화폐 거래에 참여하는 모든 주체” 라는 광범위한 정의로 일반 사용자를 포함, 헌법 허락 이상의 감시를 담고 있습니다. 이렇게 정교한 법안을 암호화폐 초짜인 의원이 짧은시간안에 내놓았음에 옐른과 같은 재무쪽의 움직임이 아니냐는 음모론도 보입니다.

4️⃣.충분한 검토가 이루어지지 않은 상태
미국도 현재 이 암호화폐시장에 대한 정의부터 방향, 규제에 대한 범위들이 토의되고 있지만 분명한 시각의 차이도 확연히 들어나고 있습니다.  불확실함 가운데 미국의 역할과 파급력은 굉장할거라 생각합니다. 충분한 검토를 거쳐 차근차근 발전되기를.

이번 법안의 수정을 위해 Toomey의원과 Wyden의원이 함께 힘쓰고 있으며 몇일 내로 수정안에 대한 결과가 나오겠습니다.  결과가 나오면 물론 비트커뮤니티가 빠르게 소식을 전달하겠지만 저도 가능한데로 전하도록 하겠습니다.

### 8/4 수요일

브로커를 명확하게 정의하는 수정안이 제안되었습니다.
 추가된 부분은
“이하의 비지니스와 연관된 사람들 제외한다.
a.트랜젝션을 검열,즉 채굴
b.하드웨어,소프트웨어지갑 판매,
c.개발자”

이제 수정안이 통과되면 되겠습니다.

>A) validating disctributed ledger transactions,<br>
B)selling hardware or software for which the sole function is to permit a person to control private keys which are used for accessing digital assets on a distributed ledger, or<br>
C)developing digital assets or their corresponding protocols for use by other persons, provided that such other persons are not customers of the person developing such assets or protocols.

### 8/5 목요일

마지막 수정안이 급하게 나왔는데 두가지가 변하게 되었습니다.  채굴의 의미가 협소하게 축약되었고 더욱 애매한 부분은 개발자 부분이 삭제되었습니다.  채굴이란 단어 사용대신 용어를 순화해서 작업증명을 넣은듯 보이는데 그 외 채굴방식이 빠지게 되었고 개발자를 왜 뺏는지 알수없습니다..

>A) validating distributed ledger transactions through proof of work (mining), or <br>
B) selling hardware or software the sole function of which is to permit persons to control a private key (used for accessing digital assets on a distributed ledger).

아 생각해보니 이 법안 아래에선 IRS가 미친척 하고 원하면 노드 돌리는 저도 포함될 수 있습니다.

아시다시피 인프라법안과 관련해서 뜬금없는 불똥이 이쪽으로 튀었죠.  첫번째 수정 후 두번째 어이없는 수정이 되었는데  워싱톤포스트에 짐작대로 옐른과 재무부가 뒤에서 움직이고 있었다는 보도가 떴군요. 명확한 목적이 있다고 볼 수 있겠습니다. 토요일 투표입니다.

<https://www.washingtonpost.com/politics/2021/08/06/crypto-bitcoin-infrastructure-senate/>

### 8/7 토요일

다시 수정안이 나왔습니다.
두번째 페이지를 보면 PoW부분이 제외되면서 나아지긴 했습니다. 개발자부분은 아직 개선되지 않았습니다.

<div class="tweet">
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Senator <a href="https://twitter.com/MarkWarner?ref_src=twsrc%5Etfw">@MarkWarner</a> and <a href="https://twitter.com/SenatorSinema?ref_src=twsrc%5Etfw">@SenatorSinema</a> have offered a new amendment with tech neutral language. If cloture is invoked, there will be 30 hours of debate left, then they will vote on the base text. We still don’t have any indication when they are going to vote on amendments. <a href="https://t.co/4IpiFkfpud">pic.twitter.com/4IpiFkfpud</a></p>&mdash; Perianne Boring (@PerianneDC) <a href="https://twitter.com/PerianneDC/status/1424053413675950091?ref_src=twsrc%5Etfw">August 7, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

현 상황으로는 작업증명과 지분증명이 제외된 상태입니다.  아직도 뜨거운 내부 논쟁중이라고 합니다.

### 8/8 일요일

들리는 소식이 맞다면 지난 월요일 부터 토론되고 제안되었던 모든 수정안 자체를 적용하지 않고 상원리더 민주당 척슈머가 그냥 밀어부친듯.<br>

그럼 일요일에 통과된 그대로 나가는듯 하네요.

더 확인은 해보야겠지만 좋아보이진 않습니다.

>D) any person who (for consideration) is responsible for regularly providing any service effectuating transfers of digital assets on behalf of another person

“voted to invoke cloture” 오늘 더 이상의 토론과 수정을 마친다는 결의안을 통과시켰습니다.

루미스 상원의원이 방금 올린 트윗에 의하면

화요일 투표 전 내일 한번 더 기회가 있을듯 하고 그래도 긍정적이라고 합니다.  전 약간 기대를 버렸습니다 ㅋ

“척슈머 상원은 빠르게 투표하고 넘어가길 원하며 수정안 투표않기를 바라고 있다.  우린 막다른 골목에 있긴하다.”

<div class="tweet">
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">This has been an interesting day. Here’s what is happening: First, we’ve been able to have very productive conversations with senators on all sides of this issue, and if we could vote on amendments I think the digital asset community would be pleased with the outcome.</p>&mdash; Senator Cynthia Lummis (@SenLummis) <a href="https://twitter.com/SenLummis/status/1424556793506635776?ref_src=twsrc%5Etfw">August 9, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

잠들기 전에 마지막으로 방금올라온 크루즈 상원의원 트윗을 나눕니다

"의견충돌로 인해 민주당이 앞으로의 모든 수정안을 받아들이지 않기로 했다. Wyden-Lummis 수정안과 내 수정안은 투표조차 되지 않게됬다. 크립토 이해하는 의원은 5명도 안된다. 위험하고 무모하다."

<div class="tweet">
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">🚨Crypto got screwed tonight.🚨<br><br>There’s a partisan disagreement on spending, so Dems objected to ALL further amendments.<br><br>That means NO vote on Wyden-Lummis to lessen the damage this bill will do to crypto, &amp; NO vote on the Cruz amd. to repeal the new crypto rules altogether.</p>&mdash; Ted Cruz (@tedcruz) <a href="https://twitter.com/tedcruz/status/1424558384335015939?ref_src=twsrc%5Etfw">August 9, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>


### 8/9 월요일

상원리더 첫슈머가 막지 않겠다 밝히면서 [워너 포트맨 시네마]파와 [투미 와이덴 루미스]파가 합의를 이뤘다는 소식이 들려옵니다.

지난 8/1 일요일 시작되어 엎치락뒤치락 수정안을 거치며 결국 pow, pos 설명 없이 "장부확인을 제공하는 서비스” 로 채굴을 정의하게 됬습니다

Here we go!

4:12pm 현재 상원의원들에게 수정안에 대해 소개되고 있습니다.  **상원의원중 한명이라도 반대하면 채택되지 못합니다**.

![](https://i.ibb.co/fdxJN8g/E8-X-u49-X0-AITFIr.jpg)

4:45pm 알라바마 상원의원 Shelby 가 국방비를 $50b 늘리는 자신의 법안을 포함해달라는 요청으로 반대하며 수정안이 무산되었습니다.

정적이 흐르고

즉시 택사스 크루즈가 바로 자신의 크립토 수정안을 채택해달라고 요청하지만 다시한번 Shelby가 국방비를 다시한번 포함하라고 반대하며 무산됩니다. 💀

<hr>

이렇게 크립토 수정안이 부결되면서 지난 일요일에 통과된 채굴자와 개발자 모두를 포함하여 국세청 보고 임부를 적용하는 법안이 내일 통과될 예정입니다.

이제 상원 통과를 마치면 하원으로 가서 하원에서 토론과 투표를 거쳐 수정안이나 반대가 되면 상원으로 오게되는데 그 때 다시 투표를 거쳐서 통과되면 대통령에게 전달되서 싸인하면 법으로 인정되어 2023년에 시작될겁니다.

이곳에서 계속 업데이트 하겠습니다.
