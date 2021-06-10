---
title: Josh Motes BBQ
subtitle: E-commerce Web App
date: "2019-05-11"
thumb_image: images/josh_motes_bbq_thumb.webp
thumb_image_alt: "Josh Motes BBQ Dozer Plate"
image:
image_alt:
seo:
  title: Josh Motes BBQ
  description: E-commerce Web App
  extra:
    - name: "og:type"
      value: website
      keyName: property
    - name: "og:title"
      value: Josh Motes BBQ
      keyName: property
    - name: "og:description"
      value: E-commerce Web App
      keyName: property
    - name: "og:image"
      value: images/josh_motes_bbq_thumb.webp
      keyName: property
      relativeUrl: true
    - name: "twitter:card"
      value: summary_large_image
    - name: "twitter:title"
      value: Josh Motes BBQ
    - name: "twitter:description"
      value: E-commerce Web App
    - name: "twitter:image"
      value: images/josh_motes_bbq_thumb.webp
      relativeUrl: true
layout: project
---

Josh Motes BBQ is a once clandestine Texan BBQ business operating from the owner's yard in Portland that was quickly needing to expand operations. Previously, the business was run entirely through private messages on Facebook, with orders having to be sent through chat and payments done individually through Paypal. This was a time consuming process, and it left room for several things to go wrong along the way, in particular with the uncertainties brought along by the start of the pandemic. My task was to <mark>automate</mark> this process, and provide a website that would serve to facilitate ordering, while allowing for set customer slots to be in place so there would not be more orders than there would be food being prepared for grilling.

![](/images/josh_motes_bbq-wireframes.webp)

The client’s vision was for the website to be clean and appear just like the printed menu my brother at [OG Illustration](https://www.instagram.com/og.illustration/) had created, but <mark>interactive</mark> and able to process payments. The client also needed to be able to customize the menu, and display only the items that he would be grilling on any particular cookout day.

![](/images/josh_motes_bbq_5.webp)

Once customer slots run out for the day, a <mark>Google Firebase</mark> connection triggers a closure of additional orders for all visitors and changes the headings and checkout text (it also sends an alert to all current viewers on the website when there is only one slot remaining to warn and entice). The website is a lean and efficient platform that serves all key information fast and allows the client to focus completely on grilling.

![](/images/josh_motes_bbq_2.webp)

In fact, the whole ordering process can be done <mark>directly on the homepage</mark> without needing to navigate anywhere else, making it quick and easy for customers to open the website and start making an order. All of the presentation mirrors exactly how the print menu appears and so returning patrons know what to expect and new customers have a description of each item.

![](/images/josh_motes_bbq_3.webp)

The website was built as a progressive web app that does order calculations and interactions on the client-side, and then using <mark>server-less functions</mark>, fulfill orders with <mark>Stripe</mark> and also decrease available slots for each successful transaction. This allowed all interactions to take all in the homepage without invoking any modules or screen transitions.

![](/images/josh_motes_bbq_4.webp)

This project allowed the client to not have to worry about processing incoming orders as Stripe handles everything, including automatically depositing the funds into his bank account. This has saved the entire operation time and resources while being an easy and <mark>user-friendly</mark> way for customers to make orders. We're hoping for a long and safe grilling season in Summer 2021, and since the web app was built with expansion in mind, looking to add order tracking and text alerts so customers instantly know when their orders are ready.


