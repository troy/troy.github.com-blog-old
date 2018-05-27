---
layout: post
title: "Chrome loves auto-play, but do users?"
date: 2018-05-27 10:46:01 -0700
comments: true
categories:
---

After [many](https://news.ycombinator.com/item?id=17036803#17037992), [many](https://news.ycombinator.com/item?id=16367457#16370471) [examples](https://news.ycombinator.com/item?id=17008991#17009630) that:

1. In some cases, users don't want Chrome to auto-play any videos – even muted ones (mostly because sites abuse the privilege by autoplaying unrelated overlay videos), and
2. Users incorrectly think Chrome's `chrome://flags/#autoplay-policy` flag disables auto-playing videos, when it only affects auto-playing videos that aren't muted

As of this writing, Chrome's actual [policy](https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#new-behaviors) is that "Muted autoplay is always allowed."

I've responded a few times on Hacker News to clarify the current behavior (see above links). The confusion and the unmet demand for disabling autoplay entirely, at least for certain domains, led me to and [tweet](https://twitter.com/troyd/status/994578157058441217) inviting the Chrome product management team to respond, then when they didn't, to [comment on the Chromium bug tracker](https://bugs.chromium.org/p/chromium/issues/detail?id=840866#c126).

Google has never explained nor substantiated its decisions to allow muted autoplay by default, and not let users change that policy, at least globally and perhaps on a per-site basis. Since Google has a clear conflict of interest, both decisions justify more transparency than they've been given.

I don't have any data about user preferences for muted auto-play. I do know that no one likes the current behavior and that Chrome has per-domain controls for far less frequently used – and less polarizing – features, like whether to clear cookies on exit.
