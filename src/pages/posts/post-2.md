---
layout: ../../layouts/MarkdownPostLayout.astro

title: My Second Blog Post
author: Astro Learner
description: "After learning some Astro, I couldn't stop!"
image:
  url: 'https://docs.astro.build/assets/arc.webp'
  alt: 'The Astro logo on a dark background with a purple gradient arc.'
pubDate: 2022-07-08
tags: ['astro', 'blogging', 'learning in public', 'successes']
---

## After a successful first week learning Astro, I decided to try some more. I wrote and imported a small component from memory!

layout: ../../layouts/MarkdownPostLayout.astro
title: My Fourth Blog Post
author: Astro Learner
description: "This post will show up on its own!"
image:
url: "https://docs.astro.build/default-og-image.png"
alt: "The word astro against an illustration of planets and stars."
pubDate: 2022-08-08
tags: ["astro", "successes"]

---

This post should show up with my other blog posts, because `import.meta.glob()` is returning a list of all my posts in order to create my list.
