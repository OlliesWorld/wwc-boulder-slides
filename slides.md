---
# try also 'default' to start simple
theme: default

layout: intro
image: 'ollie_river.jpeg'
---

<div class="ml-4 absolute top-10">
  <span class="font-700">
    by Roni 💙
  </span>
</div>

<div class="absolute bottom-10 ml-4">
  <h1>Why I use Headless CMS</h1>
  <p>Presentation/demo of how to use CMS</p>
</div>


 

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
 

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    My intro
  </div>
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
 

  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    What is CMS?!
  </div>
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
 
  <div
    class="text-3xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Headless CMS?!!?
  </div>
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

<div grid='~ cols-2 gap-4'>
<div>
I am a self-taught frontend developer. I worked with horses for the first few adult years. 2019 I started my journey into tech with online course, after I was hooked I went down the rabbit hole of tutorials. Currently working at Postman as a Software Engineer. Working with the marketing and open technologies teams to build features, component and pages.<br/>

<img src="/smile.png" class="contain w-1/2" alt="Roni and Ollie, dog, smiling wide">
</div>
<div>
I live in Fort Collins, Colorado with my pup Ollie! We love to hike, bike and paddle board. And also hang out on patios at our favorite breweries so Ollie can meet all the people! He is also the best at helping me debug!!🐶
<img src="/ollielikes.jpeg" class="cover w-1/2 " alt="Ollie,dog, looking at camera with a heart icon over his head">
</div>
</div>
<!--I needed to find something else,  when your body doesn't recover as fast and you are always working pay check to pay check. What made me jump into tech was after a few years working in customer service jobs but never able to give the customer the service I felt they needed through the ecommerce side of things. 
I started looking around for a more flexible career path and have always gotten along with computers and curious about websites. Found a tiny bootcamp/workshop course and found I loved frontend. And here we are.-->

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
image: https://www.digitalsilk.com/wp-content/uploads/2020/09/headless-content-menagament-system.jpg
---

# What is HEADLESS CMS??!!

Headless CMS is a content management system (CMS) without a pre-built front-end presentation layer or templating system; instead, it provides a content repository and an API** for managing the content. 
<!-- Basically, plugin and play with different sources, CDN, databases and much more. -->

2 main types of Headless CMS
- API Driven(83)
- Git-based(20)
According to Jamstack.org

<!-- you can probably guess which is more popular in the new API-first world. -->

<div grid="~ cols-2 gap-4">

referenced resources: <br/>
[Wiki](https://en.wikipedia.org/wiki/Headless_content_management_system)<br/>
[image source](https://www.digitalsilk.com/digital-trends/headless-cms/)<br/>
[Netlify article](https://www.netlify.com/blog/complete-guide-to-headless-cms/) <br/>
[Sanity Blog](https://www.sanity.io/headless-cms)<br/>



more: <br/>
[A very long list of Headless CMS](https://jamstack.org/headless-cms/)<br/>
[The Headless Club](https://theheadlessclub.com/)<br/>
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
- chatbots
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
And of course I use Netlify to host for a few reasons. Ease, security, cost 💰. The main one is the free forms that come with all plans.
<br/>
<br/>

<br/>
<br/>
The best part of <strong>Jamstack</strong> tech is they are pretty friendly and can work in many different combos!
---

## transition: fade

# Demo Time 

# Steps TBD

1. Login/Create Sanity account.
2. Create project - Name it My Plants
3. get project ID
4. [Clone this repo](https://motion.vueuse.org/).
5. npm install
6. Open in IDE

```html
<div v-motion :initial="{ x: -80 }" :enter="{ x: 0 }">Slidev</div>
```

---

Thank you!
Be sure to check out Strapi and TinaCMS for some variety!
