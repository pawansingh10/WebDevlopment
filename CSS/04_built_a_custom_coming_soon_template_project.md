### Build a custom coming soon template Project

The goal of the webpage is simple the website is not yet up. It shows up a coming soon websoye that can easily we transformed into an email collection form or 
can be used for varierty of other purposes.<br>
The intension here is website is not yet ready, we want to put a coming soon page and how quickly we can design it just with HTML and CSS.<br>

We can do it at much fast by using 3rd party library, but here we will do using HTML CSS way.<br>

The 1st step is to just put up the content, The faster you put up the content, the easier it is for you to design.<br>

Obviously you can use all the sematics like navigation pages and what not main, section. Sematics are always a good idea.<br>

But Here we will go with a div with a container, This a common practice to wrap everything in a container. It's easier for styling purpose.<br>

Once you're inside the container you can place blocks as many as you wish. Later on you can also modify this<br>

We will have one block which we will call it as content keeping the future in mind that there might be another that can con come up inside this container.
This is a content container another could be image container may be client ask hey can you add us a logo on the left hand side and content on the right hand side.<br>


- **padding: 2rem**, rem is such a unique unit, which we don't use most often bacuz It is relative to the M. Each of the font have different width which the
  font is taking and there is a that if you measure the M, Yes letter M, How much width letter M is taking that is considered as one unit.  that's your M,
  relative to the M


- **Can we change the better font so that they stand out? Yes, you can do so but How?**
There is a google font available however there are variety of fonts in the market but google font is the easiest one and  most used by people and popular one.<br>
[Google Font](https://fonts.google.com/)<br>
**Select font** whichever you like<br>
Once you click on that you will **Get font** and you can **Embed the code**<br>
Now it will allows you to Embed the code in different ways :-<br>
1. You can link it.<br>
2. You can just import it.<br>
Depends on what styling you're using.<br>
Again link is pretty simple Add the link in your ```head``` tag <br>
Link : Embed code in the <head> of your html
```html
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MIT Landing Page</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100..900&display=swap"
      rel="stylesheet"
    />
  </head>
```
Import : Embed code in the <head> of your html
```html
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100..900&display=swap');
</style>
```
Import : Embed code in your CSS at the very top
```
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100..900&display=swap');
```

- Not only font, you can go little bit more fancy with SVG patterns
  [svg web generator](https://getwaves.io/)<br>
  There're SVG you can generate.<br>
  Generate it either download or copy theSVG code itself<br>
  Once you have SVG code in itself, you can add this SVG as an element on your website and can add position as absolute to very bootom of the page and can
  work with that.<br.

```html
<style>
  svg {
    position: absolute;
  }
</style>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
      <path
        fill="#5000ca"
        fill-opacity="1"
        d="M0,96L20,101.3C40,107,80,117,120,138.7C160,160,200,192,240,213.3C280,235,320,245,360,213.3C400,181,440,107,480,64C520,21,560,11,600,42.7C640,75,680,149,720,154.7C760,160,800,96,840,96C880,96,920,160,960,165.3C1000,171,1040,117,1080,90.7C1120,64,1160,64,1200,96C1240,128,1280,192,1320,213.3C1360,235,1400,213,1420,202.7L1440,192L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z"
      ></path>
    </svg>

```


