---
layout: page
title: Support
---

<style>
.faq {
  border-bottom: 1px solid #eee;
}
.faq > summary {
  cursor: pointer;
  font-weight: 600;
  padding: 0.7rem 0.2rem;
  list-style-position: outside;
}
.faq > summary:hover { color: #2a7ae2; }
.faq[open] > summary { color: #2a7ae2; }
.faq > summary + * { margin-top: 0.3rem; }
.faq > *:last-child { margin-bottom: 1rem; }
.faq-group { margin-top: 2rem; }
.faq-fig { text-align: center; margin: 1rem 0; }
.faq-fig img { max-width: 100%; height: auto; }
.faq-phone {
  display: inline-block;
  background: #1c1c1e;
  padding: 5px;
  border-radius: 16px;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.22);
}
.faq-phone img { display: block; width: 160px; border-radius: 11px; }
</style>

Answers to the questions people ask most. If yours is not here, email
[support@lgias.com](mailto:support@lgias.com) and it probably will be soon.

<h2 class="faq-group">Setting up</h2>

<details class="faq" id="power" markdown="1">
<summary>How do I power the Board?</summary>

Any USB-C power source: a wall charger, a battery pack, a laptop, or your phone
itself. There is no battery inside it and no on/off switch. It starts working as
soon as it has power.

<p class="faq-fig"><img src="/assets/m5nanoc6_power.jpg" alt="The Water Polo Board plugged into a USB battery pack with a short USB-C cable" style="max-width: 280px;" loading="lazy"></p>

</details>

<details class="faq" id="connections" markdown="1">
<summary>What connects to what?</summary>

Two things, and only one of them is pairing.

Your phone pairs with the Board once, over Bluetooth, the same way you pair a
set of headphones. After that they find each other on their own.

The Board does not pair with the pool's scoreboard. It only listens to it. That
is why there is nothing to plug in at the scoreboard end, nothing to configure
on the timing equipment, and nothing to ask the table crew for.

{% include board-flow.html %}

</details>

<details class="faq" id="headset" markdown="1">
<summary>How do I connect a referee headset?</summary>

Put the headset into pairing mode with a long press on the call button, the
green one on most radios, then pair it in iOS Settings, under Bluetooth, like
any other headset. Water Polo Referee Companion speaks through whatever your
phone is playing audio to.

<p class="faq-fig"><img src="/assets/referee-radio.png" alt="A referee radio, with the green call button that puts it into pairing mode" style="max-width: 300px;" loading="lazy"></p>

</details>

<h2 class="faq-group">At the pool</h2>

<details class="faq" id="working" markdown="1">
<summary>How do I know it is working?</summary>

Look at the status at the top of the screen. "Receiving", with the period, clock
and score filling in, means the Board is hearing the scoreboard right now. "No
scoreboard data" means it is not hearing one yet.

<p class="faq-fig"><span class="faq-phone"><img src="/assets/refcompanion-main.png" alt="The app showing Receiving, with the period, game clock, shot clock and score" loading="lazy"></span></p>

</details>

<details class="faq" id="no-data" markdown="1">
<summary>The app is not showing any data</summary>

Work through these in order.

1. Check the Board has power.
2. Ask for the game clock to be run for ten seconds or so, and watch the app
   while it runs. This is the step people skip, and it is the one that most
   often fixes it.
3. In the app, open the Board and choose Select Scoreboard, then let it search
   while the clock is running.
4. If more than one turns up, pick the one whose clock matches the one you can
   see on the wall.

</details>

<details class="faq" id="equipment" markdown="1">
<summary>Do I need to know anything about the pool's equipment?</summary>

No. You do not need to know the make or model, you do not need any settings from
it, and you do not need permission or access to it. The app searches for what is
on the air and shows you what it finds.

The only thing that helps is having the clock running while it searches. Some
timing systems transmit continuously and some only transmit while the clock is
moving, and there is no way to tell which one a pool has by looking at it. Run
the clock and the question does not arise.

</details>

<details class="faq" id="placement" markdown="1">
<summary>Where do I put the Board, and how far away can I be?</summary>

There are two distances, and they are not the same.

The scoreboard's signal carries across a pool without trouble, so the Board can
sit anywhere on the deck.

Bluetooth, from the Board to your phone, is the shorter of the two. Keep them
roughly within sight of each other. If you are working the far end of the pool,
a short USB-C cable from the Board to a battery pack in your pocket keeps the
Board with you and solves it.

</details>

<details class="faq" id="lights" markdown="1">
<summary>What does the light on the Board mean?</summary>

On the Water Polo Board, with its single blue light:

- Steady: it is receiving scoreboard data.
- Slow blink: it is searching.
- Three short, three long, three short: it hears no scoreboard.
- Fast blink: it is installing an update. Leave it alone until it finishes.

Boards with a colour light show the same states as red for no scoreboard, a
breathing cyan while searching, steady cyan while receiving, and magenta during
an update.

</details>

<h2 class="faq-group">Common questions</h2>

<details class="faq" id="interference" markdown="1">
<summary>Will this interfere with the scoreboard?</summary>

No, and it cannot. The Board only listens. It never transmits anything to the
timing system, never connects to it, and never asks it for anything.

The signal it listens to is already passing through the building. Every phone at
the pool is sitting in the same radio energy; the difference is that ours has
software that understands it.

</details>

<details class="faq" id="testing" markdown="1">
<summary>Can I test it before I get to a pool?</summary>

Partly. At home you can confirm that the Board powers up and that your phone
pairs with it. You cannot confirm that it hears a scoreboard, because there is
no scoreboard to hear. The first real test is at the pool, with the clock
running.

</details>

<details class="faq" id="without-board" markdown="1">
<summary>Do the apps work without a Board?</summary>

Yes, with less.

[Water Polo Camera](/wpcam) records with the scoreboard drawn on the video, and
you enter the times by hand instead of receiving them live.

[Water Polo Log](/wplog) works fully without one; the Board only saves you from
typing times in.

[Water Polo Referee Companion](/wprefassist) needs a Board for its spoken cues,
because those come from the live clock. Its course measuring needs nothing but
the phone.

</details>

<h2 class="faq-group">Contact</h2>

**Los Gatos Integrated Applied Systems LLC**  
PO Box 272  
Los Gatos, CA 95031  
United States

General inquiries: [inquiries@lgias.com](mailto:inquiries@lgias.com)  
Product and app support: [support@lgias.com](mailto:support@lgias.com)

<script>
/* Opening a link like /support#lights should reveal that answer, not just
   scroll to a collapsed row. */
(function () {
  function reveal() {
    var el = location.hash ? document.getElementById(location.hash.slice(1)) : null;
    if (el && el.tagName === 'DETAILS') {
      el.open = true;
      el.scrollIntoView();
    }
  }
  window.addEventListener('hashchange', reveal);
  reveal();
})();
</script>
