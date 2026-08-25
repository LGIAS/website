---
layout: page
title: Apps and connected hardware
---

<style>
/* Front-page product grid. Two columns that the four cards fill evenly
   (one column on narrow phones), each card a flex column whose footer
   (badge or status) is pushed to the bottom so footers align across the
   row regardless of blurb length. */
.suite-head {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.75rem;
  margin: 1.25rem 0 0.25rem;
}
.suite-head img { width: 56px; height: 56px; border-radius: 22%; }
.suite-head h2 { margin: 0; }
.suite-intro { text-align: center; margin: 0 0 1.25rem; }
.suite-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.75rem 1rem;
  max-width: 560px;
  margin: 0 auto 1.75rem;
}
@media screen and (max-width: 480px) {
  .suite-grid { grid-template-columns: minmax(0, 1fr); }
}
.suite-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}
.suite-card img.app-icon {
  display: block;
  width: 96px;
  height: 96px;
  border-radius: 22%;
  margin: 0 auto 0.6rem;
}
.suite-card .blurb { font-size: 0.9rem; color: #555; margin: 0.3rem 0 0; }
.suite-card .card-foot { margin: 0.75rem 0 0; }
.suite-card .card-foot img { height: 40px; width: auto; }
.suite-card .card-foot em { font-size: 0.85rem; color: #888; }
/* Our own buy button, sized and colored to sit beside Apple's badge. */
.suite-card .buy-black {
  display: inline-block;
  background: #000;
  color: #fff;
  height: 40px;
  line-height: 40px;
  padding: 0 1.3rem;
  border-radius: 7px;
  font-weight: 600;
  font-size: 0.95rem;
}
.suite-card .buy-black:hover { text-decoration: none; color: #fff; }
.suite-card .spacer { margin-top: auto; }
</style>

LGIAS builds apps and connected hardware. Today, we build for water polo: tools that help parents, fans, and coaches film and follow the game, and help referees stay on top of the clock.

<div class="suite-head">
<img src="/assets/wpsuite.png" alt="Water Polo Suite">
<h2>Water Polo Suite</h2>
</div>

<p class="suite-intro">Our water polo apps and hardware, built to work together.</p>

<div class="suite-grid">
<div class="suite-card">
<a href="/wpboard"><img class="app-icon" src="/assets/wpboard.png" alt="Water Polo Board"></a>
<a href="/wpboard"><strong>Water Polo Board</strong></a>
<p class="blurb">A small wireless receiver that brings the pool's scoreboard timing to your phone.</p>
<div class="spacer"></div>
<p class="card-foot"><a class="buy-black" href="/wpboard#getting-one-is-easy">Buy now</a></p>
</div>
<div class="suite-card">
<a href="/wpcam"><img class="app-icon" src="/assets/camera-icon.png" alt="Water Polo Camera"></a>
<a href="/wpcam"><strong>Water Polo Camera</strong></a>
<p class="blurb">Film a game with the live score and clock right on the video.</p>
<div class="spacer"></div>
<p class="card-foot"><a href="https://apps.apple.com/app/apple-store/id6792160496?pt=129185827&amp;ct=lgias-website&amp;mt=8"><img src="/assets/app-store-badge.svg" alt="Download on the App Store"></a></p>
</div>
<div class="suite-card">
<a href="/wprefassist"><img class="app-icon" src="/assets/referee-icon.png" alt="Water Polo Referee Companion"></a>
<a href="/wprefassist"><strong>Water Polo Referee Companion</strong></a>
<p class="blurb">Clock and score cues in a referee's headset, and the course marks measured by the phone.</p>
<div class="spacer"></div>
<p class="card-foot"><a href="https://apps.apple.com/app/apple-store/id6792252703?pt=129185827&amp;ct=lgias-website&amp;mt=8"><img src="/assets/app-store-badge.svg" alt="Download on the App Store"></a></p>
</div>
<div class="suite-card">
<a href="/wplog"><img class="app-icon" src="/assets/wplog-icon.png" alt="Water Polo Log"></a>
<a href="/wplog"><strong>Water Polo Log</strong></a>
<p class="blurb">The digital scorebook: the game sheet writes itself.</p>
<div class="spacer"></div>
<p class="card-foot"><a href="https://apps.apple.com/app/apple-store/id6798921538?pt=129185827&amp;ct=lgias-website&amp;mt=8"><img src="/assets/app-store-badge.svg" alt="Download on the App Store"></a></p>
</div>
</div>
