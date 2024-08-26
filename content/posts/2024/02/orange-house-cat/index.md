---
title: "Orange House Cat"
description: "Death by LLM"
preview: "reCAPTCHAs are weird."
tags: ["LLMs", "Google"]
categories: ["Posts"]
date: 2024-02-15T19:42:49Z
draft: false
---

There's a weird edge case to using Large Language Models (LLMs) trained by humans that I've seen come up in Google's reCAPTCHA: Sometimes it identifies an object that resembles the one they _think_ it is, but it's not _actually_ the one they think it is.

Here's an example:

{{< figure
  src="bicycles.png"
  alt="A reCAPTCHA grid showing bicycles" default=true height="600px">}}

I've seen a few reCAPTCHAs come up like this with one of those motorbikes that aren't quite a full motorcycle (so they look bicycle-ish), but they are definitely NOT a bicycle. reCAPTCHA wants me to select the bicycle. I can't pick "nothing", because it "knows" there's a bicycle in there (and skipping doesn't teach it otherwise); But if I pick what it wants me to pick, I'm (incorrectly) reinforcing that this thing (that's not a bicycle) is, in fact, a bicycle. And since the vast, vast majority of people don't know that they're training a LLM, they just pick the thing that Google wants them to pick so that they can move on with their lives.

I guess what this means is that there might come a day when I can order an orange house cat using same-day delivery from a LLM-powered shopping app and subsequently be killed when I open the crate to find a Bengal tiger.
