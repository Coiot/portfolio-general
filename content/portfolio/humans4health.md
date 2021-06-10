---
title: Humans4Health
subtitle: Marketing and Donation Platform
date: "2019-05-10"
thumb_image: images/humans_4_health_thumb.webp
thumb_image_alt: "Humans 4 Health logo"
image:
image_alt:
seo:
  title: Humans4Health
  description: Marketing and Donation Platform
  extra:
    - name: "og:type"
      value: website
      keyName: property
    - name: "og:title"
      value: Humans4Health
      keyName: property
    - name: "og:description"
      value: Marketing and Donation Platform
      keyName: property
    - name: "og:image"
      value: images/humans_4_health.webp
      keyName: property
      relativeUrl: true
    - name: "twitter:card"
      value: summary_large_image
    - name: "twitter:title"
      value: Humans4Health
    - name: "twitter:description"
      value: Marketing and Donation Platform
    - name: "twitter:image"
      value: images/humans_4_health.webp
      relativeUrl: true
layout: project
---

Partnering with [OG Illustration](https://www.instagram.com/og.illustration/), the project was to create a social media campaign and <a href="https://humans4health.life" target="_blank" rel="noopener">website for Humans4Health</a>, a Florida non-profit focusing on building awareness around health concerns and topics. Brought in at the founding of the organization, we were to prepare all print and web materials needed for their May 28th, 2021 <mark>24-hour fitness event</mark>. The project demanded anything from Instagram templates to tent displays.

![](/images/strides_strokes.webp)

The website was my objective, while my brother prepared much of the graphics and the print media. The website needed to be fast and simple, with a clear layout to get the organization's mission well communicated, all in a tight budget. The website is my first official foray using React over my usual Vue setup. With <mark>Gatsby</mark> as the <abbr title="Static-Site Generator">SSG</abbr> and a beta invite from <mark>Stackbit</mark>, we had the core of the website up and running in less than two days.

Other than serving as a key component for the marketing campaign, the website also needed to facilitate donations coming in to support this year's event, and any future ones as well. Our choice was integrating <mark>Stripe</mark>, as it is a developer-friendly payment processor that takes in only the minimum in card processing fees, to have an in-website donation service that maximizes the amount of funds coming in and minimizes the number of clicks and frustrations from donators.

![](/images/humans_4_health_2.webp)

The setup is a very concise and direct payment form. Using Stripe's client-side only <mark>Checkout module</mark>, the form collects donations all from the website itself. In order to avoid needing a server or even server-less functions, on the client-side we could change the quantity of a set $1 dollar donation through the form so that a custom donation amount could be collected without any manipulation of payment information from the client. Admittedly a bit unorthodox, though it ensured security was kept tight.

The rest of the project also went well, with our marketing campaign doing well on Facebook. The focus is to keep growing between events, and continue building up our following and have stronger engagements on social media and our <mark>MailChimp newsletter</mark>. As of Summer 2021, the website features only its critical components; soon the blog will come online and the entire site should be receiving new updates and a fresh look in anticipation of upcoming fitness events already being planned.

![](/images/humans_4_health.webp)