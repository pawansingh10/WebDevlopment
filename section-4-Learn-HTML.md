# 🚀 Learn HTML

Basics of HTML, to write fast code by using VS Code shortcuts also better and proficient HTML code that works on any platform, anywhere.<br>
HTML is actually used on variety of interfaces, something that you know but you haven't thought that way.<br>
Example : There are a lot of screen reader on which HTML actually has to work, even on your aeroplanes when you see those screens where you watch movies, that's also HTML.<br>

There is a lot of ways How HTML is being rendered and is being used not just on mobile phones etc. It's going to be semantic and accessible.

## 🍂 What is HTML?

- **HTML** : Hyper Text Markup Language
  
- **Idea behind HTML Innovation or experiment How the HTML came into picture?** was just research paper. In earlier days scientists wanted to spread around their research work and send those
  research paper to multiple people and that's where the web was invented. At that time there was a need How can I actually on the screen or on the we can put the headings and these paragraphs and tables where
  we have put up our research paper so that We can share  it with people. That's where HTML was born.

- Idea behind HTML came up and we will have some **tags**, The way how tags are actually worked look something like <html> , almost all of the tags not every are acting as a container.

- HTML, every container starts <html> and every container ends.</html>, So **opening tag and closing tag** 

| HTML tags | Names |
|-----------|-------|
| ```<html></html>```  | HTML |
| ```<h1></h1>``` |  Heading |


- This is your basics of HTML But every single HTML doc (these documents are just as pages) that we're going to create, there pages have a precise defined structured so that they behave exactly same in
  every single browser whether it's chrome, firefox, edge etc. Browser really understand what you want to display, what you want to markup on the web on the screen.<br>
  For this we need to understand **the hierarchy of How HTML document is being made?**
  - <html>
  - <head> is meta-data, **Data about the data is known as meta data** which basically means information about the document.
  - <body>

```
<HTML>
│    
└───<head>
│   │     
│   └───<title>                 
│   
└───<body>
    │     
    └───<h1>
    │   
    └───<p>
```

- The first file that we're going to create is known as **index.html** you know why? this is because web servers are configures to pick up some of the files automatically one of them is index.html that's
  default file but there is no such hard and fast rule that we have to call it index.html always And yes you can change those configurations as well.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

- **```<!DOCTYPE html>```** In earlier days there used to be lot of many doc types bcuz browsers was serving so many of the documents HTML, different versions of HTML. Now It's just same doctype html
  Usually the 1st line of HTML is doctype html with ! which is part of syntax. It says **Hey, the document that you're about to serve on the webpage it supports the HTML and the latest version of HTML which is 5**

- **```<html>```** It just HTML, HTML has 2 parts, one is head and another is body.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>my first webpage</title>
    </head>
    <body>
        <h1>Hello from Learner</h1>
    </body>
</html>
```

- **Web Browser** doesn't obey the rule like Spaces, new line in the html for that its own way of handling the line spaces, lines break.  

---

## 🍂 Emmet, headings and block vs inline

> Note :- You don't need to learn everything in HTML! In fact nobody knows  everything in HTML. You learn on the go, on the basis of requirement basis.

- 🌺 **HTML Docs** <br>
[MDN HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Content_categories) <br>
[HTML html w3schools](https://www.w3schools.com/html/)

- 🌺 **[Emmet](https://emmet.io/)** : It used to be a plugin which need to be install exteranlly in the Sublime Text, but VS Code gives you by default So no need to install.<br>
    Emmet (formerly Zen Coding) is a set of plug-ins for text editors that allows for high-speed coding and editing in HTML, XML, XSLT, and other structured code formats via content assist.<br>
    This is an essential toolkit, something which professional people used to generate HTML and all CSS really fast.<br>
    It gives you syntax abbrevation. [Emmet Docs Syntax](https://docs.emmet.io/abbreviations/syntax/)

```html
    div>u>ul>li tab
```

  - **Emmet Lorem** : Generate dummy words <br>
```html
   h1>lorem5 tab
   h2>lorem10 tab
   h4>lorem16 tab
   p>lorem150 tab
```

- 🌺 **Headings** Heading is not about the size that h1 is big h2 is small, h3 is smaller....h6 is smallest.You can change the font-size,style,color etc by CSS. It's about relevance important which is more
    important.
  - **h1** Most important heading on your page
  - **h2** Little bit less of an important
  - **h3** Little less 
  - **h4** little little less
  - **h5** little little little less
  - **h6** least important heading of your page

**p** paragraph is just a text content.<br>
This is how usually a web page is designed.<br>

- 🌺 **Images** : ```<img src="./folder_name/image.jpg" alt="">``` <br> Here there is no closing tag for images.<br>
```html
<img src="./images/programming.png" width="300px" height="" alt="">
```

- 🌺 **Link** : anchor tag to link other pages/websites ```<a href="https://x.com"> Go to X </a>``` <br>
```htmml
    <a href="https://x.com">Go to X</a>
    <a href="mailto:infyme@proton.me">Mail to</a>
    <a href="tel:+919876543210">Mobile</a>
    <a href="./index.html">Go to index</a>
```

There is a terminology, How everything is being known like ```<h2>Lorem ipsum dolor sit amet.</h2>``` this whole thing is known as **Element** including the starting tag ```<h1>```, content ```Lorem ipsum dolor sit amet.``` and end tag ```</h2>``` So this is an h1 element.

**```<a href="https://x.com"> Go to X </a>```**, Here ```href=""```,```src="" alt=""``` is an **attribute**, these're properties of a tag, which has some **name** like href,src,alt etc etc and we pass **value** to them.<br>

- 🌺 Some of tags have property, some of them they don't have. We can addtionaly provide them.<br>

```html
  <h1 title="Hello">Lorem ipsum dolor sit amet consectetur.</h1>

  <h1 title="New tool tips">Lorem ipsum dolor sit amet consectetur.</h1>
```

- 🌺 **lists** : Lists are of 2 types, 
 - **1. UnOrdered list**```<ul></ul>``` means, List is there but order is not that much important. example : Buying Grossary items, order doesn't matter.
 - **2. Ordered List**```<ol></ol>```  means, Importance of order is there. example : Giving cooking instructions, order really matters.
```html
<ul>
       <li>Mango</li>
       <li>Apple</li>
       <li>Orange</li>
</ul>


<ol>
      <li>Read</li>
      <li>Understand</li>
      <li>Write</li>
</ol>
```

- 🌺 **Concept of Block Element and Inline Element** :
  - **Block Level Element** : The name itself suggests Block means It's a block.
  - **Inline Elements** : Inline means I will come within line the line.
  - How to figure out difference between them?
    - Block level element goes from left to right <br> It takes the entire block of your browser that's your block level element<br>
    Example : ```<h1 title="Hello">Lorem ipsum dolor sit amet consectetur.</h1> ```
    - Inline element,on the other hand they goes within the line, they don't consume or claim the territory of the entire block<br>
    Example : ``` <img src="./images/programming.png" width="300px" height="" alt="">```

 - You can go on the webpage and inspect which element is block element and hich element is inline by hovering over the element.

- 🌺 **```<div></div>```**, In the HTML, there is also known as **Container** and **div** is considered as container, div is just a wraper, a box.It doesn't do anything it's just a container.
```html
<div>
        <h1>Block level elements</h1>
        <ul>
            <li>heading h1 to h6</li> 
            <li>ol, li</li> 
            <li>ul, li</li>     
            <li>p</li> 
        </ul>
    </div>
    <div>
        <h1>Inline elements</h1>
        <ul>
            <li>a tags</li>
            <li>img</li>
            <li>strong</li>
            <li>em</li>
        </ul>
    </div>   
```

 - 🌺 **```<strong> </strong>```** strong tag and **```<b> </b>```** bold tag
```html
<p>Lorem ipsum <strong>dolor</strong> sit amet.</p>
<p>Lorem ipsum <b>dolor</b> sit amet.</p>
```
Both makes no difference when you see, But the difference between the understandability of the screen readers and the accessibilty of the website.<br>
When you say bold, It's just a bold. It doesn't do anything extra. but when you say strong that means there is some strong emphasis with this particular keyword, there is some importance of it.<br>
That's what the HTML is about. Laying down where the importance of the figure is/some word.

- **```<em></em>```** Itallic,here em is there should be emphasis on this word when screen reader read the content **```<i></i>```** Itallic, i is just a fancy nature of displaying visual hierarchy<br>

This is why all these strong tag, emphasis tag, img tag, a tag etc are inline tag, It doesn't consume end to end, doesn't create new block on its own. It does all these changes within ther place within inline.


---


## 🍂 Tables and Forms in HTML

We have seen How we can actually display the data in HTML, some of the common ways are tags like h1,h2,h3,h4,h5,h6,p,ul,ol etc and these arethe most common way to display the data.<br>
But these are not the only one, there can be so much more like keyboarf input, code, adress etc etc.<br>
You don't have to learn each of the tag, but you learn them on the go as you need them you find them and figure them out.<br>

Apart from this, There are two major way to display the data :- 
**1. How to Display tabular data** : The world is filled uo with the tabular data so we need a way how to display tables. In fact in earlier days in research work Tabular data were most important element bcuz that's
   how the findings were being printed on the research papers.<br>
   We will see how the table element is still one of the most important and most useed element.

**2. How to take data from the users?** : Important part of HTML that How we can take data from the user and that's only one way using the **forms**<br>
   **Forms** Yes, we have variety of forms<br>
   forms for HTML<br>
   forms for Email<br>'
   forms for password,files,colors,date pickers, so much of them<br>
   

### ☑️Tables

> **Read the docs, this is how you will learn with yourself without spoon feeding tutorial videos and save much of your time.**

[**mdn HTML Docs**](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/search)

- **How the table work?** : The tabular data is acutally super simple to work on with. It's really simple<br>
create a ```<table></table>``` table inside the table there is a hierarchy that you put the content inside it ```<tr></tr>``` table row and now in each of the table row we can put up some of the ```<td></td>```table data.

```html
<table>
        <tr>
            <td>Column 1</td>
            <td>Column 2</td>
            <td>Column 3</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>DOB</th>
        </tr>
        <tr>
            <td>Pawan</td>
            <td>pawan@email.com</td>
            <td>01-01-2010</td>
        </tr>
        <tr>
            <td>Pawan</td>
            <td>pawan@email.com</td>
            <td>01-01-2010</td>
        </tr>
    </table>
```
---

### ☑️ Take data from User

This is where forms come into the picture.<br>
the form on its own does nothing, It is just means of saying Hey, that we're collecting a form, we're collecting some data.<br>
But What data? You need to precisely address<br>

- Here, We can see multiple input forms for taking input from the user <br>
  - input text
  - input email
  - input password
  - input checkbox
  - input radio
  - textarea
  - submit button
  - reset button
  - select option
  - input date/month/year
  - input file
  - input color

- **```<input type="">```**, Put cursor between double quotes and press ctrl + space, auto suggestions will come.

- **place holder**
```html
            <label for="email">
                Email:<input placeholder="abc@email.com" type="email" name="email" id="">
            </label>

            <label for="password">
                password:<input placeholder="enter your password" type="password" name="password">
            </label>
```

- There is so much to learn about the form, the best way to learn is on the go.
  
---

## 🍂 Building a semantic HTML Page

We have seen enough of the basics, theoritical part of HTML like creating h1 tag, paragraph, some of the list elements and tables and forms.<br>
Now It's time to build an entire webpage, not the perfect realistic but very close to it along with the semantic of HTML.<br>

**Semantics of HTML** is really an interesting topics in which so much of amazing stuffs can happen around that.<br>
Sematic actually guides your HTML page that **How the content should be structured and wrapped around?**<br>
There used to a time when everything wrapped around just under div and now no longer this is the case.<br>
Now we actually have better sematic tags so that we can wrap around entire page and It can do so much justice to the screen readers and other places where 
your data can be consumed. <br>

Semantic is all about How your web page looks, accessible and nice for the screen reader as well as It serves a good purpose in HTML in general.<br>

- **meta tags** : These are metadata information about your webpage, how it looks like on the webport, what character set you're using UTF-8 or UTF-16 or Chinese characters, Japanese Characters, Hindi Characters then UTF structure changed.
```
UTF = "Unicode Transformation Format"
It is a standard for encoding characters in electronic communication and is widely used in computing and web development.
UTF includes various encodings such as UTF-8, UTF-16, and UTF-32, each designed to handle different character sets and requirements.
UTF-8, in particular, is the most popular encoding and is backwards compatible with ASCII.
```
  
```html
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
        </head>
```
- Sometimes you will see you load some of the scripts as well ```<script></script>```, these scripts are nothing but script which load some script external javascript or some code. It's very common thing.

- Apart from this sometimes you even load your CSS as well, ```<style></style>```, if you want to have style contents. [Play CDN](http://v3.tailwindcss.com/docs/installation/play-cdn)  

- There are 2 attributes which are very common class="" and id="" used with any element, known as global attribute.<br>
[click here](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Global_attributes)<br>
There are so many global attributes that can be injected in any of the element. These are very very helpful for the CSS.

- There used be a way designing a web page using div but now we have semantics
```html
    <body>
        <div class="header">
            <h1>Headings</h1>
        </div>
        
        <div class="footer">
            This is a footer
        </div>
    </body>
```
- HTML 5 gives us sematic tags, says hey these sematics tags are availble and try to go ahead and document or struture your website.<br>
[Sematics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)<br>
Again these sematics are container tags and they just seperate out your content little bit nothing much they don't do anything on their own. we have many of them like mentioned below<br>
 - ```<header> </header>```,```<footer> </footer>```,```<nav> </nav>```,```<section> </section>```,```<main> </main>```,```<article> </article>```<br>
   ```<summary> </summary>``` ```<figure> </figure>```

```html
    <body>
        <header>
            <h1>Headings</h1>
        </header>
    
        <footer>
            This is a footer
        </footer>
    </body>
```
- Sometime people actually wrap these heading inside another group ```<hgroup></hgroup>```<br> It is just a heading group tag.<br>
From this
```html
<body>
    <header>
        <h1>Learn to creates</h1>
        <h2>You can learn with us and build your own website.</h2>
    </header>
</body>
```
<br>
To this

```html
  <header>
        <hgroup>
            <h1>Learn to creates</h1>
            <h2>You can learn with us and build your own website.</h2>
        </hgroup>
  </header>
```
[Click here,To learn more about hgroup](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/hgroup)


> **We can auto indent our code in VS Code using the plugin called Prettier, install it and configure it from setting if it doesn't work.**


> **BTW, It does really mean that if you're putting any content at the top it will always remain at top. CSS is perfectly capable of moving any content
from top to bottom, It can change the position.**

- **```<nav></nav>```** nav element is navigation bar, usually are made of unordered lists. 

- We have seen here ```<header></header>```,```<hgroup></hgroup>```,```<article></article>```,```<time></time>```,```<section></section>```,
  ```<code></code>```,```<footer></footer>```,```<address></section>```

- We can use special character symbol like copywrite etc etc using '&' to generate special character and thanks to charset="UTF-8" which provide this stlying and encoding.
```html
<p>&copy; developer 2025</p>
```

---
