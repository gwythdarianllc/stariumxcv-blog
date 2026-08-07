---
layout: post
title: "Chronicle Report: August 2026"
date: 2026-08-07 00:05:00 -0500
---

This month 's updates are a mix of technical cleanup and polishing visuals. Here's a look at the work we did.

#### Panning and Zooming

Remember the PixieJS blockade from last month? We got through it. It turned out PixieJS never had proper multi-touch support, so multiple finger touch events just didn't register. Since we expect a lot of players to be on their phones, that's not something we could skip. So we built our own custom event manager to handle it, and it's working.

World Map:
<video autoplay loop muted playsinline style="width: 100%; max-width: 720px; display: block; margin: 0 auto;">
    <source src="/assets/video/world-zoom.webm" type="video/webm">
</video>


System Map:
<video autoplay loop muted playsinline style="width: 100%; max-width: 720px; display: block; margin: 0 auto;">
    <source src="/assets/video/system-zoom.webm" type="video/webm">
</video>

#### Codebase Cleanup

We spent some time refactoring the codebase. Looking down the road, we could see things were going to get harder to build on if we didn't clean house first, so we did. It's not the flashiest update, but it'll make everything we build next faster and easier.

#### New Icons

We're updating our icons across the board. The new set is all vector graphics, so they'll scale perfectly no matter the screen size or resolution.

![](/assets/stariumxcv-icons.png)

#### What's Next

- Management of Resources and Production
- Start implementing the Lexicon 

---

**_Thank You For Supporting StariumXCV_**

We'd love to get to know you, and we invite you to join our community on <a href="https://discord.com/invite/4aVHaRadPC" target="_blank">Discord</a>. Our devs are always around and happy to chat, whether you have questions, feedback, or just want to say hi!