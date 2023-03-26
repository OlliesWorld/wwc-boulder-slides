---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## WWC Presentation
  Presentation slides for developers.

# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Welcome to Headless CMS

Presentation about using headless CMS for developers

<div class="pt-12">
  <span  class="px-2 py-1 rounded cursor-pointer" hover="bg-red bg-opacity-10">
    by Roni <uim-rocket class="inline"/>
  </span>
</div>

<!-- <div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div> -->

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: two-cols
---
<template v-slot:default>

# Tonights Agenda!

 <div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <!-- 
     -->
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    My intro
  </div>
</div>
<div class="w-72 relative mt-6">
  <div class="relative w-40 h-40">
    <!-- -->
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    What is CMS?!
  </div>
</div>
</template>
<template v-slot:right>
<div class="w-72 relative mt-16">
  <div class="relative w-40 h-40">
    <!-- -->
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Headless CMS?!!?
  </div>
</div>
<div class="w-72 relative mt-6">
  <div class="relative w-40 h-40">
    <!-- -->
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Demo Time!!
  </div>
</div>
</template>
<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<!--
Our Agenda tonight is a fun. I want to explain a few things before we get to coding
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->
---
transition: fade-out
---
# About Me
I am a self-taught frontend developer. I am not from a traditional background as alot of us say. I worked with horses for the first few adult years. 
Currently working at Postman as a Software Engineer. Working with the marketing and open technologies teams to build features, component and pages.
<!--I needed to find something else,  when your body doesn't recover as fast and you are always working pay check to pay check. What made me jump into tech was after a few years working in customer service jobs but never able to give the customer the service I felt they needed through the ecommerce side of things. 
I started looking around for a more flexible career path and have always gotten along with computers and curious about websites. Found a tiny bootcamp/workshop course and found I loved frontend. And here we are.-->
---
transition: fade-out
---

# What is CMS?

## Content Management System
Most people know of <strong>Wordpress</strong>. Which is a On-premises installation means that the CMS software can be installed on the server. 
A monolithic system that was designed for blogs. Around 41% of the websites using Wordpress.
Why not stick with it?
### IMO
- not a CMS by todays website usages
- not secure
- slow
- big
- Always need to update plugins
- not great SEO, have to work at it

<br>

Resource [Wiki](https://en.wikipedia.org/wiki/Content_management_system)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
layout: image-right
image: https://cdn.sanity.io/images/3do82whm/next/665ee622d8843e9bd55dc8035ea21c717f410326-3388x2946.png?w=1280&h=1113&fit=clip&auto=format
---

# What is HEADLESS CMS??!!
definition:
Headless CMSes, unlike their monolithic counterparts, can deliver content to all sorts of “heads,” like mobile apps, chatbots, voice apps–anywhere content can be delivered.

<!-- Basically, plugin and play with different sources, CDN, databases and much more. -->

2 main types of Headless CMS
- API Driven(83)
- Git-based(20)
According to Jamstack.org

<!-- you can probably guess which is more popular in the new API-first world. -->

<div grid="~ cols-2 gap-4">

resources: <br/>
[Netlify article](https://www.netlify.com/blog/complete-guide-to-headless-cms/) <br/>
[Sanity Blog](https://www.sanity.io/headless-cms)<br/>
[A very long list of Headless CMS](https://jamstack.org/headless-cms/)<br/>
[The Headless Club](https://theheadlessclub.com/)


video resource: <br/>
[Sanity Video](https://www.netlify.com/blog/complete-guide-to-headless-cms/)


</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
a {
  font-size: 12px;
}
</style>

---
transition: fade-out
layout: two-cols
---
<div class="w-3xl">
 
# Why go Headless?!


<div grid="~ cols-3 gap-12">
<div class="w-md">

## Some benefits:

- 📝 **Productivity** - Editors can ship more frequently
- 📈 **Scalable** - Switch other pieces as needed
- 🧑‍💻 **Developer Friendly** - use workflows they prefer without impacting editors 
- 🎢 **Performance** - pre-renders pages and SEO out of the box
- 🔐 **Secure** - smaller area to attack, when seperate from the rest
</div>
<div></div>
 <div class="w-60">
 
## Use Cases, a few
- Websites/Web apps
- E-commerce sites
- Mobile Apps
- Products & services
- Digital signage 👀Burger King(Sanity)

</div>
</div>
</div>
---
transition: fade-out
---

# My go to stack

<div grid="~ cols-2 gap-24">
<div>
My favorite frontend framework. For me it is easy to understand and work relatively smoothly. Also, I learned about this framework at one of these WWWC talks!! <br/>Shoutout Jordan!!
<br/>
<br/>
<br/>
<img src="https://dka575ofm4ao0.cloudfront.net/pages-transactional_logos/retina/90147/Gatsby_Logo.png">


</div>
<div>
Sanity is a great way to learn CMS and they have nice sweatshirts! I chose for its price point of 3 free users. 
As an API driven CMS this one is well liked and has many tutorials. The docs are a little wonky right now since they have a new version. But they have slack channel that is active.
<!-- It is a little pricey if you need more.  I am hoping by then I will be more of an agency dev -->
<br/>
<br/>
<br/>
<img src="https://cdn.sanity.io/images/3do82whm/next/51af00784c5addcf63ae7f0c416756acca7e63ac-353x71.svg?w=2000&fm=png&dl=sanity-logo.png">

</div>
</div>



---
transition: fade
---

# Demo Time

1. Login/Create Sanity account. 
2. Create project - Name it My Plants
3.

4. [Clone this repo](https://motion.vueuse.org/).
5. npm install
6. Open in IDE

```html
<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
  Slidev
</div>
```


---
Thank you!
Be sure to check out Strapi and TinaCMS for some variety!
