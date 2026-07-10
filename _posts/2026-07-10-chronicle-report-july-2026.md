---
layout: post
title: "Chronicle Report: July 2026"
date: 2026-07-10 00:05:00 -0500
---

Fleets took center stage this month. Here's what's new.

#### Fleet UI

Fleet UI is done, and it follows the same approach as the Army UI. Splitting and moving works for both units and ships now. This was one of the hardest features to get working in the old client, so having it up and running in the new one feels like a real win.

![](/assets/stariumxcv-fleet-ui.png)

#### World Menu

The World Menu is where all your controls live for whatever's around a world. You can manage your fleets, unload armies onto new worlds, and see your beacons. Markets will be hooked up here as well.

![](/assets/stariumxcv-world-menu.png)

#### Move Handles

We upgraded the move handles for navigating orbits and moving fleets around a system. They're not perfect yet, but they're a step up from where they were.

<video autoplay loop muted playsinline style="width: 100%; max-width: 720px; display: block; margin: 0 auto;">
    <source src="/assets/video/stariumxcv-move-handles.webm" type="video/webm">
</video>

#### Small Wins

- Better metatags. Share a link to StariumXCV now and you'll get a properly sized image along with an updated name and description, so links to the game actually look good when shared.
- Improved visuals for armies and fleets moving around the map.
- Travellers Guide search results now show the actual page title instead of MediaWiki's generic "Main Page" label.

#### A Blockade!

We also hit a wall with panning and zooming. It turns out that PixieJS doesn't handle interactions the way we thought it did, so we're building our own interaction manager to replace how the game handles clicks, taps, and multi-touch gestures. The minimap is paused until that work is done.

#### What's Next

- Economics systems, including Markets and Production
- Internal playtesting, and sharing what we find
- Functional panning and zooming

---

**_Thank You For Supporting StariumXCV_**

We'd love to get to know you, and we invite you to join our community on <a href="https://discord.com/invite/4aVHaRadPC" target="_blank">Discord</a>. Our devs are always around and happy to chat, whether you have questions, feedback, or just want to say hi!