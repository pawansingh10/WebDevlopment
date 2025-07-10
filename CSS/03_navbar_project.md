## Navbar project wuth Pseudocode element

Navigation Bars are being made up of just ```ul``` elements.<br>
```html
<body>
    <div class="nav-container">
        <nav class="nav1">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Products</a></li>
                <li><button class="login-btn" type="button">Login</button></li>
            </ul>
    </div>
</body>
```
Before Start Styling let's see little bit  of flexbox go let's go to doc [click here](https://developer.mozilla.org/en-US/docs/Web/CSS/::after)<br>
**::after** : This creates pseudo element which means the element which doesn't exist.It is often used to add cosmetic content means a lot of stylings<br>

Target the element one by one.<br>

Always try to write smaller CSS, they are always good in the long term.<br>

Use pseudo property along with hover property.<br>
After property always, have content<br>
```html
.nav1 a{
            text-decoration: none;
            color: black;
            /* background-color: #d45b04; */
            padding: 5px 15px;
            
        }
        .nav1 a::after{

        }
        .nav1 a:hover::after{
            
        }
```
> CSS pro gurus actually use this, Most professionals never do this kind of stuffs in development, they usually rely on the built in component and
 those design components and they don't have these components so just go with simplistic one.

> People who love CSS go absolutely bonkers in this area and do much of the stuff with ::after etc

> Some of us are not comfortable with transition property, background and all of that. But We will see them, Hunt them, Debug them How it works.

Whenver you're learning somethings look for the errors, hunt it.<br>

| Senior Developers vs Junior Developers |
|----------------------------------------|
| **Senior Developers** have seen enough of the problems to go hunt for it and look for the exact place where the problem appears and fix it relatively faster.|
| **Junior Developers** have not seen enough so they took time to fix that's it.|

---
