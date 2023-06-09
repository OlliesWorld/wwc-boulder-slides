---
# try also 'default' to start simple
theme: default
monaco: true 
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
 
 <!-- Hi friends, thank you for coming to this event. I am hoping this is helpful for anyone interested in learning more about HeadlessCMS. I will show you 1 expample of how I use Sanity and Gatsby together. There is so many ways to use Sanity and/or HeadlessCMS 
If you have any questions please ask, I want this to be a conversation and hear your thoughts/ideas.
Let's get started. -->

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
<!-- Just giving you a heads up of what the plan is for tonight. A little bit about me. What is CMS? a brief description and examples. And then find out what is this Headless business. And finally a little demo where I show you some code. What we live for the code.
 -->
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


<!--I needed to find something else,  when your body doesn't recover as fast and you are always working pay check to pay check. What made me jump into tech was after a few years working in customer service jobs but never able to give the customer the service I felt they needed through the ecommerce side of things. 

I started looking around for a more flexible career path and have always gotten along with computers and curious about websites. Found a tiny bootcamp/workshop course and found I loved frontend. And here we are.
At postman I get to do many things with many people. Mostly with Marketing and Open Technologies Teams to build features, component and pages.
Don't ask about Ollie or I will bore you with all things. He is a very special guy.
-->

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
Most people know of <strong>Wordpress</strong>, <br>
usage is around <strong>41%</strong> of the websites.
<br>
<br>

Is Wordpress worth it? 🤔


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
NO!
ALWAYS updating plugins, Always!!
yes Wordpress can be customized with SEO and security but it will cost money and need experience

not easily customizable for non-coders(even coders)
not secure
big & slow
Always need to update plugins
not great SEO, have to work at it

And as you see not as adaptable
-->


---
transition: fade
layout: image-right
image: "/robot.png"
---

## What is 
# HEADLESS CMS??!!

<p>Headless CMS is a content management system (CMS) without a pre-built front-end presentation layer or templating system</p>
<p>In the world today there are so many types and sizes of screens. You can have the same content and display with different frontend technology.</p>


2 main types of Headless CMS
- API Driven(83)
- Git-based(20)
<br/>**According to Jamstack.org



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

<!--Headless is a mis-nomer. Multiple Adaptable Heads is probably better description but really weird name. Basically, plugin and play with different sources, CDN, databases and much more. 
Especially now a days with soo many screensizes and usage we need scalability but with flexibility.

 you can probably guess which is more popular in the new API-first world.
 -->

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

<!-- Pretty much read whats here
Really neat projects are using HeadlessCMS -->

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
As an API driven CMS this one is well liked and has many tutorials. The docs are a little wonky right now since they have a new version. But they have slack channel that is active.

As an API driven CMS this one is well liked and has many tutorials. The docs are a little wonky right now since they have a new version. But they have slack channel that is active. It is a little pricey if you need more.  I am hoping by then I will be more of an agency dev
And of course I use Netlify to host for a few reasons. Ease, security, cost 💰. A main one is the free forms that come with all plans. 
Jamstack is It enables a composable architecture for the web where custom logic and 3rd party services are consumed through APIs.
-->

---
transition: slide-down
layout: two-cols
---
# My Steps

### Frontend (Gatsby)

- Create your Gatsby repo 
- Get your layout with (dummy) data placed
- Figure out what data you want to come from Sanity
<br>

### Backend (Sanity)

- Login/Create Sanity account.
- Create project
- Download/Clone Sanity Repo
- Create your schema file -->
- add schemas to `index`
- Depoy Sanity and GraphQL
- Once deployed can edit Studio in browser or local

::right::

```js {monaco}
export default defineType({
    name: '',
    type: '',
    title: '',
    fields: [    
    defineField({
        name: '',
        title: '',
        type: '',
      }),
    ]
  })
```



<!-- depending on time talk about steps or just go quickly
I like to start with Frontend first as I usually don't have an exact plan of what I want on the page or what it will look like.
I use dummy data to create the basic structure and then start my studio -->


<!--
Make sure to redeploy Sanity and Graphql if you make changes on the studio
This where can edit schema in slide if want to explain more
defineField({
        name: 'title',
        title: 'Title',
        type: 'string',
      }),
-->


---
transition: slide-up
layout: two-cols
monaco: true 
---

### Using Sanity Data
🔹 Once data is in Sanity and deployed<br>
🔹 install <strong>gatsby-source-sanity</strong>
🔹 get project ID & add to Gatsby config(don't forget)

```js {4}
  {
      resolve: "gatsby-source-sanity",
      options: {
        projectId: process.env.SANITY_PROJECT_ID,
        dataset: "production",
      },
    },
```
🔹 Open GraphQL and find your data<br>

🔹 Create Query and copy into Page file<br>

🔹 Use data on page<br>

🔹 if using data inside a component, need static query<br>
🔹 To dynamically create pages ** more steps required

::right::
```graphql 
 export const query = graphql`
  query flower {
    allSanityFlower {
      nodes {
        id
        flowername
        slug {
          current
        }
        mainImage {
          asset {
            altText
            gatsbyImageData(
              width: 500
              placeholder: BLURRED
              layout: CONSTRAINED
            )
          }
        }
      }
    }
  }
`
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