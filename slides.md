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
  <h1>Why I use Headless CMS</h1>
  <p >Presentation/demo of how to use CMS</p>
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
<li> worked with horses </li> 
<li>2019 I started my journey into tech</li> 
<li>Currently at Postman as a Software Engineer
<li>Marketing and Open Technologies Teams to build features, component and pages</li> </li> 
</ul>
<img src="/assets/smile.png" class="contain w-1/2" alt="Roni and Ollie, dog, smiling wide">
</div>
<div>
<ul>
<li>in Fort Collins, Colorado</li>
<li> my pup Ollie, best rubber ducky there is!</li> 
</ul>
We love to 
<ul grid='~ cols-2'>
<li>hike</li> 
<li>bike</li> 
<li>paddle board</li>
<li>Camp</li> 
<li> Patio hangs at our favorite breweries</li>
<li>Ollie's loves to do anything to meet all the people!</li>
</ul>
<img src="/assets/olliecute_sticker.png" class="cover  w-1/2 m-auto" alt="Ollie,dog, looking at camera">
</div>
</div>

<!--I needed to find something else,  when your body doesn't recover as fast and you are always working pay check to pay check. What made me jump into tech was after a few years working in customer service jobs but never able to give the customer the service I felt they needed through the ecommerce side of things. 
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
Content Management System (CMS) enables users to build, organize, deliver, and modify content. With 2 types of installation: on-premises and cloud-based.
The core CMS features are: indexing, search and retrieval, format management, revision control, and management
Most people know of <strong>Wordpress</strong>. Around 41% of the websites using Wordpress.

It is very user friendly and anyone can spin up a wordpress site in minutes with little experience. And customizing is not too much work with adding plugins.
<div class=''>
Is Wordpress worth it?(IMO - No!)

<ul grid='~ cols-2  gap-2'>
<li class='text-sm'>not easily customizable</li>
<li class='text-sm'>not secure</li>
<li class='text-sm'>big & slow</li>
<li class='text-sm'>Always need to update plugins</li>
<li class='text-sm'>not great SEO, have to work at it</li>
</ul >
</div >


Resources<br/> [Wiki](https://en.wikipedia.org/wiki/Content_management_system)
<br/>[other](https://www.netsolutions.com/insights/content-management-system/)
<!--
yes Wordpress can be customized with SEO and security but it will cost money and need experience
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

<!--
Here is another comment.
-->

---
transition: fade
layout: image-right
image: https://www.digitalsilk.com/wp-content/uploads/2020/09/headless-content-menagament-system.jpg
---

## What is 
# HEADLESS CMS??!!

<p>Headless CMS is a content management system (CMS) without a pre-built front-end presentation layer or templating system; instead, it provides a content repository and an API** for managing the content.</p>

<!-- Basically, plugin and play with different sources, CDN, databases and much more. -->

2 main types of Headless CMS
- API Driven(83)
- Git-based(20)
<br/>**According to Jamstack.org

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
<br/>
And of course I use Netlify to host for a few reasons. Ease, security, cost 💰. The main one is the free forms that come with all plans.
<br/>
<br/>

<br/>
<br/>
The best part of <strong>Jamstack</strong> tech is they are pretty friendly and can work in many different combonations!

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
transition: slide-down
---
# Steps TBD
# Demo Time 


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