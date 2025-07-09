## 🚀 Learn about CSS

### 📍The current state of CSS

 CSS =  Cascading Style Sheet<br>
 The whole idea of having the CSS is **to make your website beautiful** on the mobile, on the big screen(PCs), medium screen(ipad).

 Ofcourse, we're going to learn CSS, but Let's be Honest, as a software engineer, We're not absolute 100% design person. We're more of a programming person. But this doesn't means We don't know design,
 We know foundations and basics of it, but most of us don't enjoy writting the CSS that much. But this doesn't means our website don't look that good.They look absolutely fantastic and just like any other professional design them. like websites in the corporates and for big startups, unicorns we will do the same as well.<br>

 There is a way How the CSS is written in a professional manner and how it should taught for the students who just getting started.<br>

 💥CSS is an art in itself. There're artist of the CSS available in the market like Youtube and other places. They really can nail down the designs, animations etc just kije what you see on somewhat like Apple website and other fancy websites which go crazy which we no need at the start.<br>

 We will learn enough of the basics and foundations<br>

 - 🦋 CSS has two parts : -
     1. Learning of the Foundations
     2. Making Website beautiful

> The more you know the foundation easier it to make beautiful, especially in the modern era

- In upcoming time in next 1-2 years you don't need to do everything from scratch, but you need to know enough of the foundation so that you can change the things whenever you want and however you want.
  You will know exactly where the things are not working, you know exactly when things are working and why they are working. That's exactly we're going to learn.

- We will go through the ground basics of the CSS, but before that let's see some of the Libraries and explore.

- HTML doesn't required anything, you just start writing, but also notices when we have solutions like Emmet, we were able to write out HTML faster. Exactly same like this, We have CSS libraries as well, which help us to make things easier and make our life easier.
  
- Let's so go through some of libraries and we will see how these days Applications are being built.

#### CSS

- CSS =  Cascading Style Sheet, things which **make your website beautiful** <br>
Example : Which makes you button Top-right corner, center, button of the page, stylings, colors and backgrounds all of these things is done through CSS.<br>

- But you don't have to write these CSS absolultely manually. There're some piece of code that are given to you<br>
  Examples : Some Cards, Top Navigation bars, etc you just customized them the way you want. But ofcourse this also requires CSS skills where you want to place that at the top/botton/center whereever you want.

- 🅱️**Bootstrap CSS** [Click Here](https://getbootstrap.com/)
  - First unspoken Hero of these CSS libraries is **Bootstrap**, it's little bit dated now but still many websites which use that and this will give you enough of the idea that library is being used .
  - Go to [**Bootstrap Doc**](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
  - Bootstrap look very similar on all of the website, there was one point in the web era, where almost every next website was bulit with the help of Bootstrap CSS.Although there are customizable facilities in that but Hey all of the button looks like same and there is nothing wrong in it, If it does the job. The functionality part you focusing more so in that case bootstrap works absolutely fine.

- Ⓜ️ **Materialize CSS** [Click Here](https://materializecss.com/)

- 🦜**Tailwind CSS** [Click Here](https://v3.tailwindcss.com/) Library but not exactly,It's Tailwind CSS
  - It looks weird at first but then you're going to the speed of the ability of writing the code and containerizing the code so that it can be used at any other place and it looks exactly same.
  - We will see this in details later on.
  - It's weird first and you're going to hate writing so many classes.
  - This also gives you components

- ⏹️ **shadcn/ui** [Click Here](https://ui.shadcn.com/)
  - These days getting popular, they not only give you components but they give you blocks as well. You can just copy paste this
  - Charts, Tables
  - Lots of Components - Dialogues, Show dialogues 

- 🅰️ **Acerternity UI** [Click Here](https://ui.aceternity.com/)
  - Components are just too much, like apple card, carusals

- 🟧 **Magic UI** [Cick Here](https://magicui.design/)

- 🟩 **daisyUI** [Cick Here](https://daisyui.com/)

- ⏺️ **mui** [Cick Here](https://mui.com/)

Most of them are free to use and some of them are being loved by the corporates, company buy them crazy and they give them their engineers, especially in professional environment that Hey, don't waste your time too much just make the page look decent and the basic thing like button why're you wasting so much time in buolding the button.
Once you know how it works just focus on building application.

- 🎟️ [**FlowBite**](https://flowbite.com/)
  
- 🎟️ [**Ant Design**](https://ant.design/)


> We will learn CSS, But do not get scared of the CSS. It looks scary and sometime it feels like it's too much when will I get away with it.

CSS basics and foundation, there're solutions available they make the website decent enough and it does the job.
We will learn all of it about CSS, styling of it, changing the background color, the position of it and even Tailwind CSS.<br>
You will be able to build your own component, once you have enough the basics of building 4-5 your own components, you know how the components are being designed. Now you can take the existing components and modify them however you wish to bcuz now you know how to build the components.<br>

CSS is an art and there are artists, we don't want to be that artistic. We just want to get our job done. We're more of a programming person.


---

### 📍 You can write css at 3 places

In initial days, every developer thinks that the ability to write css will make my website better, which is true. But It actually comes at third place before that - <br>

1️⃣ **Fonts** : The more beautiful the font is on the website it totally changes the look, feel, theme of the enite website with just the font. Font concume majority of the spaces on the webpage.<br>

2️⃣ **Images** : The more beautifully designed the images are and the more optimizelly and more with the idea of the flow are being designed and put on the website.

3️⃣ **Components** : How good your button looks like, how good your lists look like, cards look like.

> Whenever you designing website keep this in mind, you will be much professional in that game.

- **What we're going to do in CSS?** : The whole job of CSS is just 2 things
  - ✅ **Selecting the element**
  - ✅  **Styling the element**

- CSS stands for Cascading Style sheet, **Cascading** simply means the whole idea of flowing and giving you one style applied on the above element, it automatically cascaded to the below element as well. We will see how it works actually?



### 🚀 Ways of How we can actually style our element through CSS

- 1️⃣ **1st way is Inline styling** : Inline styling means I want to style within the line **using global attributed known as style** This is exactly the approach which Tailwind also prefers.
In any HTML element, there is a global attribute known as **style**<br>
```html
<h1 style="color: orangered">Lorem ipsum dolor sit amet.</h1>
```

This is the first way of How we can style the element.

- 2️⃣ **2nd way is of Having an style being injected in the webpage** using **style tag** within the head tag.
```html
<style>
      h2 {
        color: brown;
      }
      p {
        color: blue;
      }
    </style>
```
We can target multiple elements at the same time.
```html
<style>
      h2,p {
        color: brown;
      }
    </style>
```
Another way is **addition of attribute known as id and classes**
- Id you can have as many as you wish technically but official guideline says you should have one id on the webpage, It should be unique to one element. while on the other hand classes can be as many as you want.
- These attributes classes and Id doesn't do anything on its own. But what we can do once we have these class element is we can select those classes by dot (*) and ids by pound(#)

```html
<style>
      .browntext {
        color: brown;
      }
    </style>
  </head>
  <body>
    <h1 style="color: orangered">Lorem ipsum dolor sit amet.</h1>
    <h2 class="browntext">
      Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </h2>
   </body>
```

- 3️⃣ **3rd way is to create a new .css file** : It is a good idea that you keep your styling absolutely seperate in a separate file. It makes document a little bit easier to manipulate and manage. There're advantages of it also there're disadvantages of it as well.

Create a file style.css and select and style whatever elements you want.<br>
But It does nothing bcuz this style.css file is separate file, index.html doesn't know about it.<br>
So, let's inform index.html through link, Hey there is a style.css which want to style your elements in the start within head tag <br> 
```html
<link rel="stylesheet" href="style.css" />
```

We can have style inline```<h1 style="color: red">```, we can also have style injected through ```<style> </style>``` and we can also have external style.css file <br>
All of these three can be happens at the same time. But here comes which of the styles take over power out of these 3.<br>
Classes are more powerful, Ids are more powerful or the stying is more powerful.

---
