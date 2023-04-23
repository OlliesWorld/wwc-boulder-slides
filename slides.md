---
# try also 'default' to start simple
theme: default

layout: image
image: '/ollie_river.jpeg'
---



<div class="ml-4 absolute top-10" > 
<span class="font-700">
    by Roni 💙
 </span>
</div>

<div class="bg absolute bottom-10 ml-4">
  <h1>Let's create a Headless CMS app</h1>
  <p>A demo of how Gatsby & Sanity well work together.</p>
</div>

<style>
  .bg {
    background-color:  #05386b;
    padding: 5px;

  }
   p {
    color: white !important;
  }
</style>
 

---
transition: fade-out
layout: two-cols
preload: false
---



# Tonights Agenda!

 <div class="w-60 -ml-12 relative mt-6">
  <div class="relative w-40 h-40" >
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
    class="text-4xl font-bold absolute w-40 top-20 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    My intro
  </div>
   </div>
</div>
<div class="w-60 -ml-12 relative mt-6">
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
    class="text-4xl font-bold absolute w-100 top-20 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    What is CMS?!
  </div>
   </div>
</div>

<template v-slot:right>
<div class="w-72 -ml-12 relative mt-16">
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
    class="text-4xl font-bold absolute w-100 top-20 left-40 text-[#2B90B6] -z-1"
    v-click
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Headless CMS?!!?
  </div>
   </div>

</div>
<div class="w-72 -ml-12 relative mt-6">
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
    class="text-4xl font-bold absolute w-60 top-20 left-40 text-[#2B90B6] -z-1"
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
  background-color:  #05386b;
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
transition: slide-left
---

# About Me

<div grid='~ cols-2 gap-4'>
<div>
I am:
<ul> 
<li>a self-taught frontend developer</li>
<li>2019 I started my journey into tech</li> 
<li>Currently at Postman as a Software Engineer</li> 
</ul>
<br/>
<br/>
<br/>
<img src="/assets/smile.png" class="contain w-1/2" alt="Roni and Ollie, dog, smiling wide">
</div>
<div>
<ul>
<br/>

<li>in Fort Collins, Colorado</li>
<li> my pup Ollie, best rubber ducky there is!</li> 
</ul>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<div class='flex'>
  <img src="/assets/olliescowl.png" class="cover  w-1/2 m-auto" alt="Ollie, dog, scowling at camera">
  <img src="/assets/olliecute_sticker.png" class="cover  w-1/2 m-auto" alt="Ollie,dog, looking at camera">
</div>
</div>
</div>

<!--I needed to find something else,  when your body doesn't recover as fast and you are always working pay check to pay check. What made me jump into tech was after a few years working in customer service jobs but never able to give the customer the service I felt they needed through the ecommerce side of things. 
Marketing and Open Technologies Teams to build features, component and pages
I started looking around for a more flexible career path and have always gotten along with computers and curious about websites. Found a tiny bootcamp/workshop course and found I loved frontend. And here we are.-->

<style>
h1 {
  background-color:  #05386b;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: slide-up
---

# What is CMS?

## Content Management System
Content Management System (CMS) enables users to build, organize, deliver, and modify content.
<ul grid='~ cols-2  gap-2'> 
<li>Coding knowledge not needed</li>
<li>Easy to setup</li>
<li>Tons of Extensions/Plugins</li>
<li>Low price point</li>
</ul>
<br/>
Most people know of <strong>Wordpress</strong>, usage is around 41% of the websites.
<br/>


Is Wordpress worth it? 
 <!-- <img src="/assets/olliecute_sticker.png"  class="cover w-1/2 ml-24" alt="Ollie,dog, looking at camera"> -->




<!--
yes Wordpress can be customized with SEO and security but it will cost money and need experience

not easily customizable
not secure
big & slow
Always need to update plugins
not great SEO, have to work at it

-->

<style>
h1 {
  /* background-color:  #05386b; */
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade
layout: image-right
image: "/robot.png"
---

## What is 
# HEADLESS CMS??!!

<p>Headless CMS is a content management system (CMS) without a pre-built front-end presentation layer or templating system</p>
<p>In the world today there are so many types and sizes of screens. You can have the same content and display with different frontend technology.</p>
<!-- Basically, plugin and play with different sources, CDN, databases and much more. -->

2 main types of Headless CMS
- API Driven(83)
- Git-based(20)
<br/>**According to Jamstack.org

<!-- you can probably guess which is more popular in the new API-first world. -->

<div grid="~ cols-2 gap-4">




</div>

<style>
  .slidev-layout h1 + p {
   opacity: 1;
  }
h1 {
  background-color:  #05386b;
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
transition: slide-right
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

<style>
  .slidev-layout h1 + p {
   opacity: 1;
  }
h1 {
  background-color:  #05386b;
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
---

# My go to stack

<div grid="~ cols-3 gap-24">
<div>
<br/>
<br/>
<img class='w-3/5' src="https://dka575ofm4ao0.cloudfront.net/pages-transactional_logos/retina/90147/Gatsby_Logo.png" alt="Gatsby.js logo">

</div>
<div>
<br/>
<br/>
<br/>
<img class='w-3/5' src="https://cdn.sanity.io/images/3do82whm/next/51af00784c5addcf63ae7f0c416756acca7e63ac-353x71.svg?w=2000&fm=png&dl=sanity-logo.png" alt="Sanity.io logo">

</div>
<div>
<img class='' src="https://cdn.sanity.io/images/o0o2tn5x/production/853f17bcb1c0c264dab052006ef61fcf2893987f-1200x675.gif?" alt='Netlify logo Gif'>

</div>
</div>
<br/>
<br/>
<br/>
<br/>
<br/>🗣️ Shoutout Jordan!!

<style>
  .slidev-layout h1 + p {
   opacity: 1;
  }
h1 {
  background-color:  #05386b;
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


<!--Sanity is a great way to learn CMS and they have nice sweatshirts! I chose for its price point of 3 free users. 
As an API driven CMS this one is well liked and has many tutorials. The docs are a little wonky right now since they have a new version. But they have slack channel that is active.Sanity is a great way to learn CMS and they have nice sweatshirts! I chose for its price point of 3 free users. 
As an API driven CMS this one is well liked and has many tutorials. The docs are a little wonky right now since they have a new version. But they have slack channel that is active. It is a little pricey if you need more.  I am hoping by then I will be more of an agency dev
And of course I use Netlify to host for a few reasons. Ease, security, cost 💰. The main one is the free forms that come with all plans. 
Jamstack is It enables a composable architecture for the web where custom logic and 3rd party services are consumed through APIs.
-->

---
transition: slide-down
---
# Steps 
### Frontend First!
<br/>

1. Create your Gatsby repo 
2. Get your layout with data placed
3. install <strong>gatsby-source-sanity</strong>
4. Login/Create Sanity account.
5. Create project- either use Sanity template or clone this repo
6. get project ID & add to Gatsby config(don't forget)
7. Add data to Sanity
8. Depoy Sanity and GraphQL
9. Pull in data to Gatsby side


---
layout: image
image: '/ollie_river.jpeg'
transition: fade-out
class: text-right
---
<div class="bg"> 

## Thank you!

<br/>
<p>Be sure to check out Strapi and TinaCMS for some variety!</p>
<p>Would love to see what projects you create with Headless CMS. I am always willing to help!</p>
</div>

<style>
.bg{
  width: 50%;
  margin-left: 30rem;
  background-color:  #05386b;
  text-align: center;
  padding: 1rem;
}
p {
  
 width: 95%;
 /* margin-left: 5rem; */
}

</style>

---
transition: fade-out
---
## Resources
<br/> 

[Wiki Definition](https://en.wikipedia.org/wiki/Content_management_system)

[another definition](https://www.netsolutions.com/insights/content-management-system/)

[Wiki Headless Definition](https://en.wikipedia.org/wiki/Headless_content_management_system)

[Netlify Guide article](https://www.netlify.com/blog/complete-guide-to-headless-cms/) <br/>

[Sanity blog about headless](https://www.sanity.io/headless-cms)<br/>

[An interactive list of Headless CMS](https://jamstack.org/headless-cms/)<br/>

[The Headless Club](https://theheadlessclub.com/)<br/>

[Sanity Video](https://www.netlify.com/blog/complete-guide-to-headless-cms/)

[image source](https://www.digitalsilk.com/digital-trends/headless-cms/)<br/>