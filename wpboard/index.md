---
layout: page
title: Water Polo Board
---

<p style="text-align: center;"><img src="/assets/wpboard.png" alt="Water Polo Board icon" style="width: 160px; max-width: 45%; height: auto; border-radius: 22%;"></p>

Water Polo Board is a small wireless receiver you bring to the pool. It feeds live timing and score to the [Water Polo Camera](/wpcam) and [Water Polo Referee Companion](/wprefassist) apps over Bluetooth. It only listens; it never transmits to or interferes with the scoreboard equipment.

## How it works

The pool's scoreboard already broadcasts its timing wirelessly. The board quietly listens to that broadcast and passes it along to your phone over Bluetooth. That is the whole job: a receiver, one way, always listening and never talking back.

## Getting one is easy

<style>
.board-buy-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  column-gap: 1rem;
  margin: 1.25rem 0;
}
@media screen and (max-width: 560px) {
  .board-buy-grid { grid-template-columns: minmax(0, 1fr); }
}
/* Each card is a subgrid spanning the same five rows (title, photo, steps,
   button, footnote), so rows and buttons align across the two cards. */
.board-buy-col {
  display: grid;
  grid-template-rows: subgrid;
  grid-row: span 5;
  align-items: start;
  border: 1px solid #e8e8e8;
  border-radius: 12px;
  padding: 1rem 1.1rem;
}
.board-buy-col h3 { margin: 0 0 0.6rem; }
.board-buy-col .btn-row { text-align: center; margin: 1rem 0 0.5rem; }
.board-buy-col .buy-btn {
  display: inline-block;
  background: #2a7ae2;
  color: #fff;
  height: 40px;
  line-height: 40px;
  padding: 0 1.4rem;
  border-radius: 8px;
  font-weight: 600;
}
.board-buy-col .buy-btn:hover { text-decoration: none; color: #fff; }
.board-buy-col .badge-img { height: 40px; width: auto; vertical-align: middle; }
.board-buy-col .fine { font-size: 0.85rem; color: #777; align-self: end; margin-bottom: 0; }
</style>

The board runs on an affordable, off-the-shelf developer board about the size of a stick of gum. Get one ready to go from us, or build your own in a few minutes; it is the same board and the same firmware either way, so pick whichever suits you:

<div class="board-buy-grid">
<div class="board-buy-col">
<h3>Ready to pair, from us</h3>
<p style="text-align: center;"><img src="/assets/m5nanoc6.png" alt="M5Stack NanoC6 Water Polo Board" style="width: 110px; height: auto; border-radius: 9px;"></p>
<ol style="margin: 0.6rem 0 0.8rem; padding-left: 1.4rem;">
<li><strong>M5Stack NanoC6</strong>, our firmware installed.</li>
<li><strong>Order</strong>: $14.99 + tax + shipping.</li>
<li><strong>Pair</strong> with the app.</li>
<li><strong>That's it.</strong></li>
</ol>
<p class="btn-row"><a class="buy-btn" href="https://buy.stripe.com/aFa3cu4Shci86cmc9Fg3600">Buy now</a></p>
<p class="fine">Ships by USPS within the US. Outside the US? <a href="mailto:inquiries@lgias.com">Email us</a> and we will work something out.</p>
</div>
<div class="board-buy-col">
<h3>Build it yourself</h3>
<p style="text-align: center;"><a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><img src="/assets/m5nanoc6.png" alt="M5Stack NanoC6" style="width: 110px; height: auto; border-radius: 9px;"></a></p>
<ol style="margin: 0.6rem 0 0.8rem; padding-left: 1.4rem;">
<li><strong>M5Stack NanoC6</strong>, flash it yourself.</li>
<li><strong>Order</strong> from Amazon.</li>
<li><a href="/flash"><strong>Flash</strong></a> our free firmware.*</li>
<li><strong>Pair</strong> with the app.</li>
</ol>
<p class="btn-row"><a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><img class="badge-img" src="/assets/available-at-amazon.png" alt="Available at Amazon"></a></p>
<p class="fine"><a href="https://www.amazon.com/s?k=esp32-c6+dev+board&amp;tag=lgias-20" target="_blank" rel="noopener">Other ESP32-C6 boards</a> work too.<br>* The one-time flash needs a <a href="https://www.amazon.com/s?k=usb-c+data+cable&amp;tag=lgias-20" target="_blank" rel="noopener">USB-C data cable</a> and a computer running Chrome or Edge.</p>
</div>
</div>

<small>As an Amazon Associate, LGIAS earns from qualifying purchases.</small>

Either way, it could not be lower maintenance: keep it in its antistatic bag, power it from any <a href="https://www.amazon.com/s?k=usb+power+bank&amp;tag=lgias-20" target="_blank" rel="noopener">USB power bank</a> (you can even plug it into your phone), and it starts listening. Once set up, the board keeps itself up to date through the app over Bluetooth.

## Our own board is in the works

We are also designing our own board from the ground up. Below are the board design and an early working prototype.

<p style="text-align: center; margin: 1.5rem 0;">
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 22px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: top;"><img src="/assets/wpboard-c-cad.png" alt="Board layout for our own Water Polo Board, revision 2" width="200" style="display: block; border-radius: 16px;"></span>
<span style="display: inline-block; background: #1c1c1e; padding: 6px; border-radius: 22px; box-shadow: 0 4px 16px rgba(0, 0, 0, 0.28); margin: 0.4rem 0.45rem; vertical-align: top;"><img src="/assets/wpboard-c-prototype.jpg" alt="Working prototype of our own Water Polo Board, coming soon" width="200" style="display: block; border-radius: 16px;"></span>
</p>

---

<small>* Compatible systems include wireless water polo timing from Colorado Time Systems. LGIAS is not affiliated with, endorsed by, or sponsored by Colorado Time Systems, which is a trademark of its respective owner.</small>
