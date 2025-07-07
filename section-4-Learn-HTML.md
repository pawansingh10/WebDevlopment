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

### 🧀 Emmet, headings and block vs inline

> Note :- You don't need to learn everything in HTML! In fact nobody knows  everything in HTML. You learn on the go, on the basis of requirement basis.

- **HTML Docs** <br>
[MDN HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Content_categories) <br>
[HTML html w3schools](https://www.w3schools.com/html/)

- **[Emmet](https://emmet.io/)** : It used to be a plugin which need to be install exteranlly in the Sublime Text, but VS Code gives you by default So no need to install.<br>
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

- **Headings** Heading is not about the size that h1 is big h2 is small, h3 is smaller....h6 is smallest.You can change the font-size,style,color etc by CSS. It's about relevance important which is more
    important.
  - **h1** Most important heading on your page
  - **h2** Little bit less of an important
  - **h3** Little less 
  - **h4** little little less
  - **h5** little little little less
  - **h6** least important heading of your page

**p** paragraph is just a text content.<br>
This is how usually a web page is designed.<br>

**Images** : ```<img src="./folder_name/image.jpg" alt="">``` <br> Here there is no closing tag for images.

**Link** : anchor tag to link other pages/websites ```<a href="https://x.com"> Go to X </a>``` <br>

There is a terminology, How everything is being known like ```<h2>Lorem ipsum dolor sit amet.</h2>``` this whole thing is known as **Element** including the starting tag ```<h1>```, content ```Lorem ipsum dolor sit amet.``` and end tag ```</h2>``` So this is an h1 element.

**```<a href="https://x.com"> Go to X </a>```**, Here ```href=""```,```src="" alt=""``` is an **attribute**, these're properties of a tag, which has some **name** like href,src,alt etc etc and we pass **value** to them. Some of tags have property, some of them they don't have. We can addtionaly provide them.<br>

```html
  <h1 title="Hello">Lorem ipsum dolor sit amet consectetur.</h1>
```















---
