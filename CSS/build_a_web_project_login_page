## 🏦 Building a web project - Login Page

One way to learn CSS is : walk through all the ** CSS Selectors** , walk through all the **CSS Properties** ,<br>
Like How can we change the border radius, add padding, add margin, change text color, change background color etc <br>
Yes, we can learn in this way.<br>

The faster way to learn CSS is through **to build projects**

> **Projects are the only way to learn CSS** - Flexbox

Flexbox is one such thing which allows you to position certain element at a certain position on the webpage. It's relatively easy. We will see flexbox in details later on.<br>
Here we will see How we can centalize any element horizontally and vertically in webpage using flexbox.

---

### 🧑‍💻 Let's build the login page 

We will have a card in the center with the heading Login<br>
User input Email<br>
User input Password<br>
Login Button<br>

1. First step is put out the content which means Get your HTMl done
2. Then style CSS using inline or in style tag  taking each element or by creating attributes class and Id also just little bit of flexbox.

---

### 💳 Masterclass on CSS Selectors

- **Selectors** : Selectors is the ability to select any element on the webpage.<br>
There are varierty of ways of doing so. This a rabbit whole you can go as much as depth as you wish. But in professional environment we won't work like that.<br>
People prefer to choose the simplistic way to select the element on the webpage.<br>

---
open x.com(twitter), you will see weird classes names something which professional developer definately not write names like that. This raises the question is it really professional code 
is being written in these website? No that's not the case. This is not how it's being written.<br>
majority of professional high websites, they actually use some or the other tools behind the scene which generates the CSS for them, which generate this elements and that's why classes names 
you have seen is weird to you.<br>

Foundation and basics is still css but there're internal tools, one such tool is **tailwind CSS** which is now publicly available to everyone. Tailwind is moreover inspired by
the facebook set of tools, facebook follows the principle of Atomicity and Atomic CSS in all of their tools like Insta,Facebook,Web Whatsapp, Thread etc.

---

- **How can you select an Element?**
  - Easiest way is to add **classes**, that's the easiest one of all.
  - But professional CSS people, they actually urge to atleast walk through the other selectors that're available. We will see 10 of them.
 

Before moving to code part, Let's understand that **HOw the web structure is being populated**<br>
Raw HTML file which is plain vanilla HTML and the way how HTML website is actually loaded on the web page is known as DOM<br>

DOM stands for Document Object Model, whever you actually work with DOM, that means how your page is structured, how it is laid out, that is your Document document object model. 
So this is the **ability of transforming your HTML code into an object model or a tree that can be rendered by the browser**. We will see DOM in details in JS.<br>

Let's see we have a div inside that 3 elements h1 p img  another div inside div which further containing a p.
So here 1st div is parent div and the 2nd div is child of div 1.<br>

> Generally we can see 3 relationship, **Parent-Child** and **Descendants or Relatives** **siblings**, This is the whole idea of DOM which helps you to understand selectors little bit better.

- We will learn about the Parent, Child, Descendant or Relatives & siblings and How can we work with them?

- **1. Universal Selector** :
   - Every single browser, they introduce some of their own CSS not all CSS but at least minimum like h1 font is little bigger than h6 is also a part of CSS which browser introduces for you
     paddings, margins. So what we do is remove default minimum CSS of all the browsers. But How?
   - There is way to flush out all the styling being given by browser. Almost all frameworks Bootstrap, Tailwind, Ant Design gives you a way to do it.
   - This is done using * which means everything
```html
<style>
    *{
        margin : 0;
        padding : 0;
        boz-sizing : border-box;
     }
</style>
```
- **2. Type Selectors** :
   - Type Selectors means I will tell you what element I'm selecting on the webpage. It could be h1 or p.
   - Example : Select all the paragraphs p
```html
<style>
    p {
      font-size : 16px;  
      margin : 10px 20px 10px 20px;
      padding : 1px 2px 3px 4px;
      boz-sizing : border-box;
     }
</style>
```

- **3. Class Selectors** :
  - There can be multiple classes according to specification on a webpage, and by using that specific class you can target that specific element.
  - There're frameworks and libraries which generates classes for you. like Tailwind.

```html
<style>
    .highlight {
      background-color : yellow;
     }
</style>

<h2 class="highlight">Welcome to the yellove army.</h2>

```

- **4. Id Selectors**:
    - According to specification you shpuld have only one id for one web page. But HTML doesn't give you error.

```html
<style>
    #header {
      background-color : yellow;
     }
</style>

<h2 class="highlight" id="header">Welcome to the yellove army.</h2>

```
> HTML and CSS has variety of ways how you can put colors into Elements e.g : most common is **Hex Color code**, hsl(hue saturation lightness % opacity you want), rgb(red,green,blue).
We never prefer to write these value as red, green, blue or white etc bcuz every browser has different ways of rendering the webpage some of them have different red shed while others
have different and we don't want inconsisting in branding that's why preferred value is hex color code

- **4. Attribute Selectors** :
   - Attribute selectors are interesting, you just have to name what is the element and what kind of attribute you are targeting
   - You can optionally enter what kind of value in that attribute

| Paranthesis | Braces | Square Bracket |
|-------------|--------|----------------|
|     ( )     |  { }   |     [ ]        |
  
---
