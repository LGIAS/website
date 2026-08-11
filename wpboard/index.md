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
  gap: 1.25rem;
  margin: 1.25rem 0;
}
@media screen and (max-width: 560px) {
  .board-buy-grid { grid-template-columns: minmax(0, 1fr); }
}
.board-buy-col {
  border: 1px solid #e8e8e8;
  border-radius: 12px;
  padding: 1rem 1.1rem;
}
.board-buy-col h3 { margin: 0 0 0.6rem; }
.board-buy-col .buy-btn {
  display: inline-block;
  background: #2a7ae2;
  color: #fff;
  padding: 0.55rem 1.4rem;
  border-radius: 8px;
  font-weight: 600;
}
.board-buy-col .buy-btn:hover { text-decoration: none; color: #fff; }
.board-buy-col .fine { font-size: 0.85rem; color: #777; }
.board-buy-col .pick {
  display: flex;
  align-items: center;
  gap: 0.7rem;
  margin: 0.8rem 0;
}
.board-buy-col .pick img { width: 56px; height: auto; border-radius: 8px; flex-shrink: 0; }
.board-buy-col .pick div { font-size: 0.9rem; }
</style>

The board runs on an affordable, off-the-shelf developer board about the size of a stick of gum. Get one ready to go from us, or build your own in a few minutes; it is the same board and the same firmware either way, so pick whichever suits you:

<div class="board-buy-grid">
<div class="board-buy-col">
<h3>Ready to pair, from us</h3>
<p style="text-align: center;"><span style="display: inline-block; background: #1c1c1e; padding: 5px; border-radius: 14px;"><img src="/assets/nanoc6.webp" alt="M5Stack NanoC6 Water Polo Board" style="display: block; width: 110px; height: auto; border-radius: 9px;"></span></p>
<p><strong>$14.99</strong> + shipping and tax. An M5Stack NanoC6 with the firmware already installed and tested: nothing to flash, nothing to set up. Pair it with the app and go.</p>
<p style="text-align: center; margin: 1rem 0 0.5rem;"><a class="buy-btn" href="https://buy.stripe.com/aFa3cu4Shci86cmc9Fg3600">Buy now</a></p>
<p class="fine">Ships by USPS within the US. Outside the US? <a href="mailto:inquiries@lgias.com">Email us</a> and we will work something out.</p>
</div>
<div class="board-buy-col">
<h3>Build it yourself</h3>
<p>Buy a board, then load the free firmware by <a href="/flash">setting it up in your browser</a>: a one-time step that takes a couple of minutes. Any of these works:</p>
<div class="pick">
<a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><img src="/assets/nanoc6.webp" alt="M5Stack NanoC6"></a>
<div><a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><strong>M5Stack NanoC6</strong></a>: the smallest, in a tidy little box.</div>
</div>
<div class="pick">
<a href="https://www.amazon.com/dp/B0D2NKVB34?tag=lgias-20" target="_blank" rel="noopener"><img src="/assets/xiao-c6.jpg" alt="Seeed XIAO ESP32C6"></a>
<div><a href="https://www.amazon.com/dp/B0D2NKVB34?tag=lgias-20" target="_blank" rel="noopener"><strong>XIAO ESP32C6</strong></a>: small and beginner-friendly.</div>
</div>
<div class="pick">
<a href="https://www.amazon.com/dp/B0DCGB5QSR?tag=lgias-20" target="_blank" rel="noopener"><img src="/assets/devkitm.png" alt="ESP32-C6-DevKitM-1 developer board"></a>
<div><a href="https://www.amazon.com/dp/B0DCGB5QSR?tag=lgias-20" target="_blank" rel="noopener"><strong>ESP32-C6 dev board, 2-pack</strong></a>: a dependable workhorse, and you get a spare.</div>
</div>
<p class="fine">You will need a <a href="https://www.amazon.com/s?k=usb-c+data+cable&amp;tag=lgias-20" target="_blank" rel="noopener">USB-C data cable</a> and a computer running Chrome or Edge for the one-time setup.</p>
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
