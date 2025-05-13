---
description: Playwright
public: true
layout: ../../layouts/BlogPost.astro
title: 🔒 Solving Cloudflare Turnstile CAPTCHAs
createdAt: 1714113713426
updatedAt: 1714113846371
tags:
  - Playwright
heroImage: /img/2captcha1.png
slug: oofos-o-oahh
---

![2captcha](/img/2captcha.png)

In the ever-evolving landscape of web scraping and automation, encountering CAPTCHAs — especially Cloudflare Turnstile — is almost inevitable. This article breaks down a practical script that uses Playwright, 2Captcha, and proxy servers to bypass these challenges and continue automation tasks seamlessly.

<h1>🧠 Key Technologies Used :</h1> <p>Playwright: A powerful Node.js library to automate browsers.

2Captcha: A CAPTCHA solving service that supports Cloudflare Turnstile.

Proxies: Used to mask your IP and avoid rate limits or bans.

JavaScript Injection (inject.js): Intercepts Cloudflare token parameters from the frontend.</p>

![2captcha](/img/2captcha2.png)

<h1>🧪 How It Works (In Simple Terms) :</h1>
You visit a page that uses Cloudflare Turnstile.

A custom inject.js script captures CAPTCHA data and logs it in the browser console.

The main script picks up this log, extracts CAPTCHA parameters.

Sends them to 2Captcha to be solved.

Once the token is received, it's injected back into the page to pass the CAPTCHA.
