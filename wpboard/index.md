---
layout: page
title: Water Polo Board
---

<p style="text-align: center;"><img src="/assets/wpboard.png" alt="Water Polo Board icon" style="width: 160px; max-width: 45%; height: auto; border-radius: 22%;"></p>

Water Polo Board is a small wireless receiver you bring to the pool. It feeds live timing and score to the [Water Polo Camera](/wpcam) and [Water Polo Referee Companion](/wprefassist) apps over Bluetooth. It only listens; it never transmits to or interferes with the scoreboard equipment.

## How it works

The pool's scoreboard already broadcasts its timing wirelessly. The Board quietly listens to that broadcast and passes it along to your phone over Bluetooth. That is the whole job: a receiver, one way, always listening and never talking back.

<style>
/* Three separate photographs laid out as a chain, rather than one wide image,
   so each caption sits under its own object and the row can stack on a phone. */
.flow {
  display: grid;
  grid-template-columns: 1fr 76px 1fr 76px 1fr;
  align-items: start;
  gap: 0.5rem;
  max-width: 700px;
  margin: 1.75rem auto 0;
}
.flow-art { height: 170px; display: flex; align-items: center; justify-content: center; }
.flow-art img { display: block; width: auto; }
.flow-console img { height: 142px; }
.flow-board img { height: 150px; }
.flow-phone { background: #1c1c1e; padding: 4px; border-radius: 14px; box-shadow: 0 3px 12px rgba(0, 0, 0, 0.22); }
.flow-phone img { height: 152px; border-radius: 10px; }
.flow-cap { text-align: center; font-size: 0.9rem; line-height: 1.35; margin-top: 0.5rem; }
.flow-cap span { color: #777; }
.flow-hop { height: 170px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 0.4rem; }
.flow-hop-label { font-size: 0.75rem; color: #888; text-align: center; white-space: nowrap; }
.flow-hop svg { display: block; }
.flow-hop .wave-v { display: none; }
.flow-note { text-align: center; margin: 1.1rem 0 1.75rem; }
/* Stacked on a phone: the chain runs top to bottom, so the arcs are redrawn
   pointing down rather than rotated, which would leave them in a sideways box. */
@media screen and (max-width: 560px) {
  .flow { grid-template-columns: minmax(0, 1fr); gap: 0; max-width: 320px; }
  .flow-art { height: auto; }
  .flow-console img { height: 118px; }
  .flow-board img { height: 126px; }
  .flow-phone img { height: 132px; }
  .flow-hop { height: auto; flex-direction: column; gap: 0.3rem; margin: 0.9rem 0; }
  .flow-hop .wave-h { display: none; }
  .flow-hop .wave-v { display: block; }
}
</style>

<div class="flow">
<div>
<div class="flow-art flow-console"><img src="/assets/console.jpg" alt="The wireless tabletop controller the table crew operates at the scorer's table"></div>
<div class="flow-cap"><strong>Pool scoreboard system</strong><br><span>broadcasts scoreboard data.</span></div>
</div>
<div class="flow-hop">
<div class="flow-hop-label">over the air</div>
<svg class="wave-h" viewBox="0 0 28 60" width="34" height="73" fill="none" stroke="#2a7ae2" stroke-width="2" stroke-linecap="round" aria-hidden="true">
<path d="M6.43 22.34 A10 10 0 0 1 6.43 37.66"></path>
<path d="M11.57 16.21 A18 18 0 0 1 11.57 43.79"></path>
<path d="M16.72 10.08 A26 26 0 0 1 16.72 49.92"></path>
</svg>
<svg class="wave-v" viewBox="0 0 60 28" width="73" height="34" fill="none" stroke="#2a7ae2" stroke-width="2" stroke-linecap="round" aria-hidden="true">
<path d="M22.34 6.43 A10 10 0 0 0 37.66 6.43"></path>
<path d="M16.21 11.57 A18 18 0 0 0 43.79 11.57"></path>
<path d="M10.08 16.72 A26 26 0 0 0 49.92 16.72"></path>
</svg>
</div>
<div>
<div class="flow-art flow-board"><img src="/assets/m5nanoc6_power.jpg" alt="The Water Polo Board, about the size of a stick of gum, plugged into a USB power bank"></div>
<div class="flow-cap"><strong>Water Polo Board</strong><br><span>relays scoreboard data.<br>(powered over USB)</span></div>
</div>
<div class="flow-hop">
<div class="flow-hop-label">Bluetooth</div>
<svg class="wave-h" viewBox="0 0 28 60" width="34" height="73" fill="none" stroke="#2a7ae2" stroke-width="2" stroke-linecap="round" aria-hidden="true">
<path d="M6.43 22.34 A10 10 0 0 1 6.43 37.66"></path>
<path d="M11.57 16.21 A18 18 0 0 1 11.57 43.79"></path>
<path d="M16.72 10.08 A26 26 0 0 1 16.72 49.92"></path>
</svg>
<svg class="wave-v" viewBox="0 0 60 28" width="73" height="34" fill="none" stroke="#2a7ae2" stroke-width="2" stroke-linecap="round" aria-hidden="true">
<path d="M22.34 6.43 A10 10 0 0 0 37.66 6.43"></path>
<path d="M16.21 11.57 A18 18 0 0 0 43.79 11.57"></path>
<path d="M10.08 16.72 A26 26 0 0 0 49.92 16.72"></path>
</svg>
</div>
<div>
<div class="flow-art"><span class="flow-phone"><img src="/assets/wpcam-record.jpg" alt="A phone recording the game with the scoreboard drawn on the video"></span></div>
<div class="flow-cap"><strong>Your phone or tablet</strong><br><span>receives scoreboard data.</span></div>
</div>
</div>

<p class="flow-note">Nothing plugs into the scoreboard. The Board's only cable is power.</p>

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
.board-buy-col .badge-img { width: 150px; height: auto; vertical-align: middle; }
.board-buy-col .fine { font-size: 0.85rem; color: #777; align-self: end; margin-bottom: 0; }
</style>

Every Water Polo Board is the same tiny, affordable gadget, about the size of a stick of gum, running our free software. The only question is who loads the software onto it: we can do that for you, or you can do it yourself in a few minutes with a computer and a USB cable. Same Board either way:

<div class="board-buy-grid">
<div class="board-buy-col">
<h3>From us, ready to use</h3>
<p style="text-align: center;"><img src="/assets/m5nanoc6.png" alt="M5Stack NanoC6 Water Polo Board" style="width: 110px; height: auto; border-radius: 9px;"></p>
<ol style="margin: 0.6rem 0 0.8rem; padding-left: 1.4rem;">
<li><strong>Order</strong>: $19.99. Free shipping.</li>
<li><strong>Pair</strong> with the app.</li>
<li><strong>That's it.</strong></li>
</ol>
<p class="btn-row"><a class="buy-btn" href="https://buy.stripe.com/28E00ickJ6XOfMW2z5g3603">Buy now</a></p>
<p class="fine">An M5Stack NanoC6 with our software already installed and tested.<br>Ships free by USPS within the US; tax added where applicable. Outside the US? <a href="mailto:inquiries@lgias.com">Email us</a> and we will work something out.</p>
</div>
<div class="board-buy-col">
<h3>From Amazon, you set it up</h3>
<p style="text-align: center;"><a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><img src="/assets/m5nanoc6.png" alt="M5Stack NanoC6" style="width: 110px; height: auto; border-radius: 9px;"></a></p>
<ol style="margin: 0.6rem 0 0.8rem; padding-left: 1.4rem;">
<li><strong>Order</strong> from Amazon.</li>
<li><a href="/flash"><strong>Install</strong></a> our free software on the Board.*</li>
<li><strong>Pair</strong> with the app.</li>
</ol>
<p class="btn-row"><a href="https://www.amazon.com/dp/B0D8Q32F67?tag=lgias-20" target="_blank" rel="noopener"><img class="badge-img" src="/assets/available-at-amazon.png" alt="Available at Amazon"></a></p>
<p class="fine">An M5Stack NanoC6; you install our free software on it yourself.<br><a href="https://www.amazon.com/s?k=esp32-c6+dev+board&amp;tag=lgias-20" target="_blank" rel="noopener">Other ESP32-C6 boards</a> work too.<br>* The one-time setup needs a <a href="https://www.amazon.com/s?k=usb-c+data+cable&amp;tag=lgias-20" target="_blank" rel="noopener">USB-C data cable</a> and a computer running Chrome or Edge.</p>
</div>
</div>

<small>As an Amazon Associate, LGIAS earns from qualifying purchases.</small>

Either way, it could not be lower maintenance: keep it in its antistatic bag, power it from any <a href="https://www.amazon.com/s?k=usb+power+bank&amp;tag=lgias-20" target="_blank" rel="noopener">USB power bank</a> (you can even plug it into your phone), and it starts listening. Once set up, the Board keeps itself up to date through the app over Bluetooth.

---

<small>* Compatible systems include wireless water polo timing from Colorado Time Systems. LGIAS is not affiliated with, endorsed by, or sponsored by Colorado Time Systems, which is a trademark of its respective owner.</small>
