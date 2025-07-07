## 🚀 Basics of Web Development

Before we jump into the development actually writing code, It's important to understand few things<br> 
**How does the internet work?** means How does one computer connects to the another computer?

It's fascinating and surprized by How good this engineering is!<br>
Connecting one computer to another computer is state of the art engineering.

---

## 🌐 How does Internet work?

What does mean by Internet?<br>
The ability to connect one computer to another computer all round the world through through a wire called **Internet**. That's all the basics of it.<br>

But the How it does is magical and fasinating. We're able to do it all seamlessly, that's the power of engineering.

Any computer you see like google.come, instagram.com, x.com etc all are actually not known by these names, They are all known with an **IP address**<br>
The IP Address looks like 192.168.2.5 <br>
There is a entire stream of a engineering in knowing just about these IP addresses known as **Networking**. You'll see the exam in CISCO for networking.<br>

Each of the computer gets IP Address which is unique in itself. But just with IP Address you can't rememeber the IP Address.<br>

Now You have one computer which has its unique IP Address and Google.com has its own computer which also has a unique IP Address. Now can you connect both of them NO!,  It doesn't happens like that<br>

So, You have one computer which has its unique IP Address and Google.com has its own computer which also has a unique IP Address. Now can you connect both of them NO!,  It doesn't happens like that<br>

---

### 💥 Internet

- You have an **ISP** that means people from where you have bought your internet might be **Airtel, Jio, Starlink** etc. which are Internet Service Provider.
So, we simply go ahead and first connect with IP that Hey I want to connect to a website known as google.com. He says I don't know who is the owner of the google.com and I don't know How to connect that.<br>

- So, They reach out to something known as **DNS** Domain Name System. This is long phonebook of the internet and every ISP has this phonebook and It keeps on updating timely basis.
There are lot of chains to these DNS so that until it reaches out and resolve that.

- So, ISP reach out to DNS and say Hey, somebody is looking for google.com I don't know who that is, so can you give me the ip address of that? and they go ahead and look for something like [**NsLookUp.io**](https://www.nslook.io) or something they've inbuilt solution for that. and they go ahead and say Hey you were looking for google.com, Just go ahead and find its DNS record. So once you go ahead and find this DNS record, that will look like , They say Hey, this is the IP Address of it. It goes ahead and copy paste it and then it goes ahead and tell it that, This google.com is can resolve by this ip address and this is being served to ISP.

- Now **ISP provider goes to the big gigantic globe of something known as Internet, which is just a mesh of cables.**
and they try to look for this IP Address. once they go ahead and look for this ip address, they eventually find this and gives you back by saying Hey, now you're able to connect with this.

> **This whole connection process is your internet.That's all your internet.That's how it works.**

Note : Now these names google.com, facebook.com etc etc are provided by some authorities and providers which gives you these names.<br>
Eaxmple : [**GoDaddy**](https://www.godaddy.com/en-in) is famous one<br>
**Name Cheap**, **Big Rock** etc

---

### ❓ Questions that's comes in mind as a beginners

- **If my computer has an ip address, can I just host my own website?**<br>
Yes, Certainly you can do but the problem is you have to keep your computer up and running all the time.<br>
That's why there are some providers which are specilized in keeping thier computer running all the time.<br>
Example :  **Google GCP | Amazon  AWS | Microsoft Azure | Digital Ocean | Linord |** <br>

We'll How we can actually host your website so that it is up and available all the time without you worrying about. <br>

We'll not only make our website, we'll deploy our website to the production so that millions and millions of people can actually serve your project/web application.


> **✨ Summary : Mystery of Internet is not complex, It is just communication between the ISP, DNS which give you IP address and by which you're able to connect to any website that you see around**

---


## 🍀 A big picture of Web Application

Before jumping and writing HTML, CSS and JS <br>
We need to understand what happens on the web so that we can understand the Tech very well.<br>
- Different types of Databases, what role do they play and how they work?
- What's frontend?
- What's backend?

 
 ### 🕸️ How the Web Application works?

Icons and Nomenclature to understand  terminologies better.
Icons for 
HTML
CSS
JS
Database
Server
Laptop
Browser

✨ Let's understand the flow of How Application works?

You're trying to make a **request** on some website google.com, there is a server of google.com. You're trying to access this website may be trying to signup or login or access on webpage.

-  Step 1. Just go ahead and request to the server, You ask server Hey server, I want to visit a page might be Homepage/login/any other page. Now server based on your request tries to either access its database or just sends you a **response** back. If you're accessing infornation which are restricted like a login/signup then it will first verify its database that whether you're telling, who you're telling is actually the person then it will response back otherwise send you Hey, you're not authorized or your password is incorrect.
Let's assume you're trying to access the very Homepage. So the server will say the request came from this particular URL. So I need to seend back a response to this user.
Once It sends back a response, there is so much of mechanism that goes on. We can see some of them in the Chrome Networking tab that how it goes, some of the response code.

- 1️⃣ The step 1 of the **server** is to send first of all the **HTML** to the **web browser** : HTML on its own doesn't look really beautiful, but it is a sematic, It is a tructure of your webpage and that's why the name Hypertext Markup language. So It's just a markup that you will need some of the text, some paragraph, some heading. So these all information are being sent to you.

- 2️⃣ After that comes up is the **CSS** It makes things a little bit more beautiful. So the button should be at the top right/left corner or wherever it needs to go. This is the whole job of the CSS.

- 3️⃣ Finally the functionality part of the application will comes up which is through **JavaScript**, JS allows you to actually have those drop downs, search features, ability to click the button and something happen when you click the button. One of the job of JS is also to take some of your data from your browser to the server. So basically JS allows you to enable the mechanism , the functionality of the website snd that's the basic of it.

 > On a big picture that's how every single application works.

There is definately a lot more that we're going to see, Where the backend engineers work?, where the frontend engineers work? and How they communicate with each other and all the other stuffs.


> 💥 **Overview to understand what we are trying to learn, what we will able to  build and whole lot of other things.**

---

## 🍏 FrontEnd, BackEnd, APIs and Client Server

- **Frontend Part** :  HTML | CSS | JavaScript |

- **Server Part** : A lot of people believe Server is like a big machine. No It is not. Server is just a software that serves, It serves web application, It might serve something else also. That is termed as Backend 


| 🥭 **Front End**  - Fronend Engineer 🧑‍💻 |
|---------------|
|Sometimes the frontend although it looks just HTML, CSS and JS from a very big picture in some sense it is. But there are some frameworks that are introduces in it.|
|Example : HTML reamins HTML|
| But for CSS there are some libraries that comes into the pictures like **Bootstrap** which helps you to write CSS faster, **Tailwind** which helps you to write even faster and variable of the CSS much easier.|
| JavaScript it's core foundation is JavaScript but some more additional tech come into the picture to handle and make thinf=gs easy for you on the frontend side. **React**, **View and Svelt** etc alot will come and go but JS foundation remains same.|

| 🍎 **Backend** - Backend Engineer 🧑‍💻|
|-------------|
| Backend is majorly composes of two things|
| **1. Programming Language**<br> That could be JavaScript, Yes you can write full fledge backend code in Javascript, Node JS, PHP, Django, Python, Ruby on Rails etc So all of these languages, they're server side scripting languages. |
| **2. Database** <br> MySQL, MongoDB, Postgresql etc. You can learn either or both and can store your all of the information. The whole job of the database is to store the information. And there're variety and version of it. More Variety, More better it is. That's why you see so many versions of the databases. Some are SQL, some are NoSQL means store the data in the tabular format just like tables, some just store that as JSON that's new word.|

- 🅰️🅿️ℹ️**API** : Application Programming Interface, API acts as a gateway, This is a medium through which the backend and frontend are interacting which each other.<br> Right now outr frontend is JS and Backend is also JS But there could be case where our front is JS but backend is in Java or might be other language.<br>
So How does a Backend which is written in java  talks to frontend which is written in Javascript?<br>
Here, we need a common language so that any backend written in any language or frontend which is dealing in React or Core Javascript cam talk to each other. That is where API comes into the picture.<br>
So, Your frontend is going to make a request on the API endpoint, a simple door that Hey, I'm knocking the door of SignUp/Login/etc It sends a data into a universally accepted format that hey, the data is always going to come in this format and that format usually is known as **JSON** | API format that's JSON format | <br>
Example : API is compared with Waiters in the restourents, Users comes in and order for an Omelet, and now Omelet needs to prepared in the kitchen (Backend). The restaurent's table for user to served where user come, sit and order (Frontend) Like you don't go into the kitchen and take out the omelete yourself. You ask waiter (API) Hey, can you bring me an omelet and then waiter goes and bring the omelet that waiter is considere suing as an API. and the format It serve you data in the plates that's JSON.

---

[Create Diagram Web Dev Road](https://www.eraser.io/)
