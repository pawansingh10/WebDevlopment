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

## ☑️ Masterclass on CSS Selectors

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

- **5. Attribute Selectors** :
   - Attribute selectors are interesting, you just have to name what is the element and what kind of attribute you are targeting
   - You can optionally enter what kind of value in that attribute. 
```html
<style>
    input[type="text"] {
      border : 2px solid #21a2c9;
     }
</style>

<input type="text" name="" id="" placeholder="Enter text" />
```
> 80-90% of time These 4 selectors **1. Universal Selector**, **2. Type Selectors**, **3. Class Selectors**, **4. Id Selectors**and **5. Attribute Selectors** we majorily used throughout our career.

| Paranthesis | Braces | Square Bracket |
|-------------|--------|----------------|
|     ( )     |  { }   |     [ ]        |

#### These are the Advance CSS Selectors

- **6. Descendant Selectors** :
  - In order to target descendant selector, It's little weird. Read it as ``` all the p which are decendant of article```
```html
<style>
    article p {
      font-size: italic;
      background-color: #1a1a1a;
      color: white;
      padding: 10px;
     }
</style>

<input type="text" name="" id="" placeholder="Enter text" />
```

- **7. Child Selectors** :
   - It's actually nice, Child != Descendant

```html
<style>
    div > p {
      list-style-type: square;
      background-color: #1a1a1a;
     }
</style>

<div>
    <p>child</p>
    <p>child</p>
    <section>
         <p>descendant</p>
    </section>
    <p>child</p>
</div>
```

- **8. Adjacent Siblings Selectors** :
   - read h1 + p as all the p who are adjacent siblings of h1
```html
<style>
    h1 + p {
      font-weight: bold;
      background-color: #1a1a1a;
     }
</style>
```
- **9. General Siblings Selectors** :
   -  all the p which are general siblinga of h2
```html
<style>
    h2 ~ p {
      font-weight: bold;
      background-color: #1a1a1a;
     }
</style>
```
- **10. Pseudo-class Selector** :
   - We will use it quite alot
   - A lot of HTML element properties, they have different behaviours when you select the input, different behaviour when you mouse hover it and
     you can control all of these properties based on what element you are targetting.
   - Common thing you're going to see is hover property, like We want to select all the a tags and we only want to implement the CSS whenever there is
     a hover motion in action on that.   
```html
<style>
    a:hover {
      background-color: #1a1a1a;
      text-decoration: none;
      color: #1a1a1a;
      padding: 5px;
      margin: 4px;
     }
</style>
```

- **11. Pseudo-element Selector** :
   - Pseudo-element Selectors are crazy altogether on another level.
   - I want to select all the first letters in the all paragraphs
```html
<style>
    p::first-letter {
      font-weight: bold;
      font-weight: bold;
     }
</style>
```

- **12. Grouping Selector** :
   - 
```html
<style>
    h1,h2,h3 {
       color: #1a1a1a;
     }
</style>
```

---

## ☑️ Box Model, Inline and Block elements

- 🍊**Box Mode**

This is one of the most foundational concept in the CSS and in general of the web elements.<br>
How much space an element is going to consume on your website or on your webpage. It is governed by what kind of model or what ind of Box model it is following.<br>

There are actually two box model which are generally there, Now browser should actually change the default behavior of everything to the box model because that's what everybody is using whether you use Bootstrap, Tailwind or any other framework of the future, Box model is the way to go.<br>

It is safe to assume that whenever you're flushing out everything from browser, just change the model behavior to the box model.<br>
This is so common that people are even arguing and commenting to the Web3 authorities, Hey now just allow every browser to set a default browser into the box model.

> Sometimes It is much more important to understand the code than rather writing the code.

> See what's happening, analyze it and then understand it!

 There are 2 browser content box models that means how much space the element is going to take on your web browser.
1️⃣ The default behavior of browser is **Content Box**, this is going to change<br>
    
2️⃣ Another is **Border Box** Every single frameworks library, they actually reset to Border Box from the default bahaviour of the browser.<br>

The **Content box** portrait 300px but the element doesn't consume 300px It consumes more than that it adds padding, it adds border of it.<br>
while on the **Border box** the whole element whenever you say it's 300 pixel. It's a guranteed 300 pixels and that's why everybody loves it.

- 🍊 **Inline Elements**
Inline elements takes as much space as it is required by the content in the element, and just work with that. It is inline, It doesn't breaks out of the line.

- 🍊 **Block Elements**
On the other hand Block element which consumes the entire space on left to right. You can restrict it to be little bit shorter or bigger but nobody can takes other space. It's whole consume by it.









---
