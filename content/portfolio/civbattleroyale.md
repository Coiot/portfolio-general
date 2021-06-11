---
title: Civ Battle Royale
subtitle: Image Host and Content Creation
date: "2019-04-11"
thumb_image: images/cbr_logo_thumb.webp
thumb_image_alt: "CBR logo, three hexahons within a larger hexagon with an artdeco floruish"
image:
image_alt:
seo:
  title: Civ Battle Royale
  description: Image Host and Content Creation
  extra:
    - name: "og:type"
      value: website
      keyName: property
    - name: "og:title"
      value: Civ Battle Royale
      keyName: property
    - name: "og:description"
      value: Image Host and Content Creation
      keyName: property
    - name: "og:image"
      value: images/cbr_logo_thumb.webp
      keyName: property
      relativeUrl: true
    - name: "twitter:card"
      value: summary_large_image
    - name: "twitter:title"
      value: Civ Battle Royale
    - name: "twitter:description"
      value: Image Host and Content Creation
    - name: "twitter:image"
      value: images/cbr_logo_thumb.webp
      relativeUrl: true
layout: project
---

The Civ Battle Royale (<abbr title="Civ Battle Royale">CBR</abbr>) is a biweekly online show that creates community narrated stories based upon AI-only matches run on **Sid Mier's Civilization V**. Began in 2015, the project swelled to a huge 100k+ following, and won a <mark>Guinness World Record</mark> in 2016 for being the largest followed strategy game at the time (this was just before the mainstream emergence of Twitch).

![](/images/cbr_logo.webp)

In 2017, myself and a few teammates took over the project and began a general cleanup and rebranding of the show to keep the format and release schedules consistent. Initially I was brought on the team to create a new <mark>image host</mark> and central hub for the show as previously the program was reliant on hosting all of its content on Imgur and sharing posts only through Reddit. The project demanded a fast website that would host and distribute images to its <mark>global audience</mark>.

![](/images/cbr_1.webp)

 Because the website would be heavy on images, I decided to use a paid <abbr title="Content Distribution Network">CDN</abbr> to deliver the ever growing number of images (presently over 20,000) and a static-site generator for the pages. The combination chosen was <mark>KeyCDN</mark>, which although a pricey option over other competitors, has the best edge network to reach the most locations across the world in faster time. This was essential since each page can have over 100 good quality images. My choice for static-site generation was <mark>VuePress</mark>, since it made initial setup simple and I could create episodes by quickly formatting markdown files pushed onto Github.

![](/images/cbr_2.webp)

To create the markdown files, our team automated a process with <mark>Python</mark> and <mark>Google Cloud APIs</mark> that convert shared documents provided to community narrators that reformat their writing as YAML front-matter that would correspond with all the content on the page and each narration with its appropriate image. On the website, the YAML front-matter is converted into the content and layout. The website allows for the viewer to choose to read the episodes in *'horizontal'* mode (carousel) but defaults to *'vertical'* mode to make scrolling easier on mobile users. Horizontal mode invokes the slideshow function that was discontinued by Imgur in 2016 and was a much desired feature by the community.

![](/images/cbr_3.webp)

Additional pages on the website are dedicated to help viewers navigate through our past archive of episodes, and everything is structured in 'seasons' and 'arcs'. Because the website is <mark>fully static</mark>, everything is fast and images are lazy loaded in from the <abbr title="Content Distribution Network">CDN</abbr> as viewers move through an episode. As the project gets bigger, it has outgrown VuePress a bit, so a few optimizations have also had to been made to keep build times for hundreds of pages low (only two minutes per build at the moment).

![](/images/cbr_4.webp)

Other than managing the website, I'm also the principal <mark>content creator</mark> and <mark>community manager</mark> for the project. Over the years I've created numerous artworks, a custom subreddit theme, icons, banners, and typically make sure our automations are running smoothly. Being a content creator is exhausting at times, but it feels great being at the head of a wonderful Reddit community.

![](/images/cbr_5.webp)
