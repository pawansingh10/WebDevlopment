### ☑️ Hands on Bootstrap integration

These days Bootstrap is considered as outdated.But It is not.<br>
Bootstrap is still rocking, still shipping and you can crazily work on Bootstrap, you can built so many applications and produce then in the production with the bootstrap.<br>
Bootstrap code is still working, clients are happy, still a lot of companies built their internal applications using Bootstrap.<br>

- 📕 **But why is it Bootstrap considered as outdated?** : because people on internet requires something new over the time. They change their Designing Pattern, Designing Styles
  At one point of time everything used to be red, they somehow it became all shiny and glass looking then everything became more of like purplish or bluish now therse days
  It's all dark mode. It keeps on changing and that's why there is nothing super static in the world of Design that's why you should know the basics of CSS so that you can
  pick up the libraries and framework pretty quickly, considerably.<br>

- 📗 That's how everybody picked up **Bootstrap** at one point of time and now people got bored of it. It's not, It's outdated, It's just people are bored of it and now they want
  something new. and these days **Tailwind** is taking care of it.<br>
  
  Tailwind is not just one style, you can style things on your own and It's really nice that way.

- 📙 So you should have some wisdom about Bootstrap so that in case you require or there is any need of it, you can also work with Bootstrap and you will love it.

---

 ### ☑️ Bootstrap - How It works and How to read its [docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)?

- **What is Bootstrap? & How can we understand Bootstrap?**
   - In simple word, Somebody sat down for you and wrote so many CSS classes for you and just by putting these classes at a right place you can style your components.<br>
    e.g. : You have your button, somebody has written a class named as btn and btn-primary and you just have to inject these two classes in in your component or
           your button and that's it. Your button will look out of the beautiful.

   - Suppose you want to create a button, simple using basix btn tag. Nobody likes this kind of button specially when it's not styled, but what we can do is learn from
     Bootstrap is How can we make this button beautiful without writting a single line of CSS, we'll write a little bit not much.

   - [Bootstrap docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/) : If you look at Get started Bootstrap page, create a HTML Page, then inject
     the Bootstrap.
   - How to inject Bootstrap, which is literally a  CSS file, ofcourse It's a ```.min.css``` but at the end of the day, It's minified version of CSS. and they also give
     you a little bit of javascript as well bcuz some of the element require JS like **Accordion** which hovers there and some of the elements which as **Carousal** that
     means the images that keeps on circling. You can go ahead and work with that.

   - They also give you the CDN Link, just go ahead and copy this whole link and that's all the CSS that you would have. Let add it just below the title and link that href 
```html
<title>Boostrap Example</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css"/>
```
   - What Boostrap provide you is somebody wrote so many classes for you, all you can do is add those classes they're already available to you as we added the link to it.
```html
<div class="container">
      <button class="btn btn-primary">HeyCode</button>
      <button class="btn btn-secondary btn-ml">HeyCode</button>
      <button class="btn btn-warning btn-lg">HeyCode</button>
      <button class="btn btn-danger btn-sm">HeyCode</button>
    </div>
```
  - There're so many of variations available, but from where I will get to know where are these button what can I use? That's where the documentation of Bootstrap come
    into the picture. There's nothing magical about it. You have to go into the docs, have to study them and eventually you will learn.<br>
    Example : look for Button in Bootstrap, You will see there is a base class, every button needs to be a base class called btn and then whatever the button
              you want you can just just choose the CSS of it.

  - Bootstrap gives you so many of components, components means Button is a component, card is a component.
  
  - If you want to add card, you can do that

- There're lots of free resources, One of them is **Pexels.com[]**

You can modify your components as per your own wish 
```html
 <div class="card-body bg-primary text-white">
<a href="#" class="btn btn-primary" style="width: 100%"
            >Go somewhere</a
```

- If you want to add a nav bar, you can see there're alot of them are available.

- There're some responsive components which require Javascript, so we link javascript by taking js script from bootstrap intro section and add it just before your end.
```html
<script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ndDqU0Gzau9qJ1lfW4pNLlhNTkCfHzAVBReH9diLvGRem5+R9g2FzA8ZGN954O5Q"
      crossorigin="anonymous"
    ></script>
  </body>
```
- Focus on funtionality part, It's not just Bootstrap, we have so many of the libraries and frameworks that we can work through.

> This is enough of Basic overview of Bootstrap, If it required in your company, you can actually go and read the Bootstrap documentation and work on it.

> **Bootstrap is a course in itself.**
 
---

### ☑️ Assignement : Build an entire webpage

Design a webpage, you should use Bootstrap components as much as you like and there're some requirement for this.<br>
Here all the knowledge that you have about **Flexbox, Grid, Bootstrap and Custom CSS** all are going to come in handy.<br>

At the very top of it there should be a carousel, How big How small it depends width of the images 500px or whole page, It's up to you. Assume this should take 25% of the webpage. -> Go to bootstrap you will find that there're carousel components up there.<br>

Next is card components, needs to have exactly 3 cards. Cards Should be youtube video thumbnail and should be redirected to watch page.<br>

At the very bootom of It there should  be a footer which says copyright and yourname. Also inject copyright symbol which is using & address of operator like ```<p>&copy;Copyright</p>```

This page needs to be mobile friendly. The best part about the Bootstrap is Bootstrap does their job for their carousel, if we shrink it It will automatically It is mobile optimized, mobile responsive but the Cards are not,bcuz you're putting them. So you have to do that feel free to use flexbox, grid however you want to do that.
But on the smaller screen screen these 3 cards should not be together, they should stacked up one card above one card above on card.<br>

Also make sure whatever content you're putting on your mobile screen It should be decent on mobile screen as well. You can shrink the font on mobile devices or move copyright on another space and youname bottom of it.


```$ tree
├── Webpage
│   ├── Carousel
│   └── 3 Cards
│   └── Footer
│
├── Carousel
│   ├── image 1
│   ├── image 2
│   └── image 3
│
├── Cards 
│   ├── Youtube 1
│   ├── Youtube 1
│   └── Youtube 3
│
└── Footer
    └── @Copyrights | 2025

```

