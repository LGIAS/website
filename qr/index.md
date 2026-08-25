---
layout: page
title: QR codes
---

<style>
.qr-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
  max-width: 640px;
  margin: 1.5rem auto 0;
}
.qr-tile {
  display: block;
  border: 1px solid #e8e8e8;
  border-radius: 12px;
  padding: 1rem 0.6rem 1.1rem;
  text-align: center;
  color: inherit;
}
.qr-tile:hover { text-decoration: none; border-color: #2a7ae2; }
.qr-tile img { width: 88px; height: auto; border-radius: 20%; display: block; margin: 0 auto 0.6rem; }
.qr-tile strong { display: block; font-size: 0.95rem; line-height: 1.3; }
.qr-tile span { display: block; margin-top: 0.4rem; font-size: 0.8rem; color: #2a7ae2; }
@media screen and (max-width: 560px) {
  .qr-grid { grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 0.5rem; max-width: 100%; }
  .qr-tile { padding: 0.8rem 0.3rem 0.9rem; }
  .qr-tile img { width: 64px; }
  .qr-tile strong { font-size: 0.8rem; }
}
</style>

Tap an app to open its code full screen, then hand them the phone.

<div class="qr-grid">
<a class="qr-tile" href="/assets/qr/wpcam-qr-card.png">
<img src="/assets/camera-icon.png" alt="">
<strong>Water Polo Camera</strong>
<span>Show code</span>
</a>
<a class="qr-tile" href="/assets/qr/companion-qr-card.png">
<img src="/assets/referee-icon.png" alt="">
<strong>Water Polo Referee Companion</strong>
<span>Show code</span>
</a>
<a class="qr-tile" href="/assets/qr/wplog-qr-card.png">
<img src="/assets/wplog-icon.png" alt="">
<strong>Water Polo Log</strong>
<span>Show code</span>
</a>
</div>

Each code goes straight to that app on the App Store. Downloads from these are
counted separately from the website, so it stays clear what a conversation at a
pool is actually worth.

The [Water Polo Board](/wpboard) has no code of its own: it is not an App Store
listing, so point people at lgias.com for it.
