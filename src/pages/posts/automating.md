---
description: Puppeteer
public: true
layout: ../../layouts/BlogPost.astro
title: 📸 Automating YouTube with Puppeteer, Simulating Vision Deficiencies and Capturing Screenshots
createdAt: 1714113582611
updatedAt: 1714113668883
tags:
  - Puppeteer
heroImage: /img/script.png
slug: bisley-cabinet
---

<h1></h1>

![Script](/img/script.png)

In today’s world of web automation, Puppeteer stands out as one of the most powerful tools for headless browser scripting. In this article, we'll explore a practical Puppeteer script that demonstrates how to automate a YouTube search, simulate vision deficiencies, and capture screenshots at multiple stages in the browsing flow.

<h1>🔧 What the Script Does</h1>
This Node.js script uses Puppeteer to:

Launch a headless Chromium browser.

Navigate to YouTube.

Type a search query into the search box with a simulated typing delay.

Emulate a vision deficiency (blurred vision).

Take screenshots before and after simulating the deficiency.

Click the search button.

Wait for the search results to load.

Take a screenshot of the search results.

<h1>🧠 Key Concepts Demonstrated</h1>

Vision Deficiency Emulation
The script uses page.emulateVisionDeficiency() to simulate how a visually impaired user might experience the site.

<h1>🧪 Why This Script Is Useful</h1>
This script is a powerful demo of:

✅Automated UI testing

✅Accessibility testing

✅Browser behavior simulation

✅Visual regression testing
