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

> Learning can't be just by watching/consuming Tutorial Videos, You need to supplement it with little bit of reading official document and practice.

## Twitter style navbar in CSS

```html
<style>
    .nav2{
            border: 2px Solid red;
            background-color: #03643c;
            width: 200px;
            padding: 20px;
        }
        .nav2 ul{
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        .nav2 li{
            margin-bottom: 12px;
        }
        .nav2 a{
            text-decoration: none;
            color: white;
            display: block;
            padding: 10px;
            width: 100%;
        }
        .nav2 a:hover{
            background-color: #137e0a;
        }
        .nav2 .login-btn{
            background-color: #048a2f;
            border: none;
            color: white;
            width: 100%;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
            /* margin-left: 7px; */
        }
        .nav2 .login-btn:hover{
            background-color: #137e0a;
            border: 1px solid white;
        }
</style>
```

## Dropdown navbars and positions

Knowing the foundations and basics is good enough but eventually we will move to Tailwind/DaisyUI/Shascn etc which makes our life little bit easier.
So that we can focus on building software, building the funtionality and not just UI upgradation part.<br>

```html
.nav3{
            border: 2px solid red;
            background-color: #45a2bb;
        }
        .nav3 ul{
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        .nav3 a{
            text-decoration: none;
            color: white;
            padding: 10px;
            display: block;
        }
        .nav3 .dropdown-content{
            display: none;
            
        }
        .nav3 .dropdown:hover .dropdown-content{
            display: block;
            position: absolute;
            background-color: #202929;
            min-width: 150px;   
        }
```
---
