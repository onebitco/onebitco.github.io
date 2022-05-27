---
layout: page
title: 👨🏻
permalink: /👨🏻/
---

![Banksy Stock Market Guy Painting]({{ site.url }}/assets/img/sys/banksy.jpg)
[Banksy @ Brooklyn, NY, 2018](https://www.banksy.co.uk/)

{% include author.html %}
✉️ >> <one@bitcoinone.net><br>
✍️ >> [medium/@onebitgram](http://medium.com/@onebitgram), [twitter/onebitgram](http://twitter.com/onebitgram)<br>
⚡️ >> [1ml.com](https://1ml.com/node/0246344c2ff83905bf5b9847f50385f85834df595faedb3983bb97112dd6b8c52d)<br>
🔑 >> PGP Fingerprint<br>
9C4E FFB4 24D6 1B66 7CAA  73F4 C990 F8CE 764D B3D5

<style> .btcpay-form { display: inline-flex; align-items: center; justify-content: center; } .btcpay-form--inline { flex-direction: row; } .btcpay-form--block { flex-direction: column; } .btcpay-form--inline .submit { margin-left: 15px; } .btcpay-form--block select { margin-bottom: 10px; } .btcpay-form .btcpay-custom-container{ text-align: center; }.btcpay-custom { display: flex; align-items: center; justify-content: center; } .btcpay-form .plus-minus { cursor:pointer; font-size:25px; line-height: 25px; background: #DFE0E1; height: 30px; width: 45px; border:none; border-radius: 60px; margin: auto 5px; display: inline-flex; justify-content: center; } .btcpay-form select { -moz-appearance: none; -webkit-appearance: none; appearance: none; color: currentColor; background: transparent; border:1px solid transparent; display: block; padding: 1px; margin-left: auto; margin-right: auto; font-size: 11px; cursor: pointer; } .btcpay-form select:hover { border-color: #ccc; } .btcpay-form option { color: #000; background: rgba(0,0,0,.1); } .btcpay-input-price { -moz-appearance: textfield; border: none; box-shadow: none; text-align: center; font-size: 25px; margin: auto; border-radius: 5px; line-height: 35px; background: #fff; }.btcpay-input-price::-webkit-outer-spin-button, .btcpay-input-price::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; } </style>
<form method="POST" action="http://zceokiyohwd55mscvo2zj4eskoaxthfpg7oetgs3i3oh6oqu5kofbaqd.onion/api/v1/invoices" class="btcpay-form btcpay-form--block">
  <input type="hidden" name="storeId" value="9hhMSFmm2ApKZMkAtupjnAL4r3mwMhQPLwqXMopdGJ9n" />
  <div class="btcpay-custom-container">
    <div class="btcpay-custom">
      <button class="plus-minus" type="button" onclick="handlePlusMinus(event);return false" data-type="-" data-step="1" data-min="1" data-max="20">-</button>
      <input class="btcpay-input-price" type="number" name="price" min="1" max="20" step="1" value="1" data-price="1" style="width:3em;" oninput="handlePriceInput(event);return false" />
      <button class="plus-minus" type="button" onclick="handlePlusMinus(event);return false" data-type="+" data-step="1" data-min="1" data-max="20">+</button>
    </div>
    <select name="currency">
      <option value="SATS" selected>SATS</option>
      <option value="USD">USD</option>
      <option value="GBP">GBP</option>
      <option value="EUR">EUR</option>
      <option value="BTC">BTC</option>
    </select>
  </div>
<button type="submit" class="submit" name="submit" style="min-width:209px;min-height:57px;border-radius:4px;border-style:none;background-color:#0f3b21;" title="Pay with BTCPay Server, a Self-Hosted Bitcoin Payment Processor"><span style="color:#fff">BTCPay 기부하기</span>
<img src="http://zceokiyohwd55mscvo2zj4eskoaxthfpg7oetgs3i3oh6oqu5kofbaqd.onion/img/logo.svg" style="height:57px;display:inline-block;padding:5% 0 5% 5px;vertical-align:middle;">
</button></form>
<script>
    function handlePlusMinus(event) {
        event.preventDefault();
        const root = event.target.closest('.btcpay-form');
        const el = root.querySelector('.btcpay-input-price');
        const step = parseInt(event.target.dataset.step) || 1;
        const min = parseInt(event.target.dataset.min) || 1;
        const max = parseInt(event.target.dataset.max);
        const type = event.target.dataset.type;
        const price = parseInt(el.value) || min;
        if (type === '-') {
            el.value = price - step < min ? min : price - step;
        } else if (type === '+') {
            el.value = price + step > max ? max : price + step;
        }
    }

    function handlePriceInput(event) {
        event.preventDefault();
        const root = event.target.closest('.btcpay-form');
        const price = parseInt(event.target.dataset.price);
        if (isNaN(event.target.value)) root.querySelector('.btcpay-input-price').value = price;
        const min = parseInt(event.target.getAttribute('min')) || 1;
        const max = parseInt(event.target.getAttribute('max'));
        if (event.target.value < min) {
            event.target.value = min;
        } else if (event.target.value > max) {
            event.target.value = max;
        }
    }
</script>

🏁 시작 >> [Intro - never settle](https://bitcoinone.net/etc/2021/what.html)<br>
🙇🏻‍ 감사 >> [Thank You Isn't Enough. 감사합니다](https://bitcoinone.net/etc/2021/thank-twitter.html)
