## 📳 Breakingpoints for Mobile Tablet and Web

How to design Mobile Responsive website?<br>
We will not write code from  scratch to just to make sure that one webpage is designed for the mobile and for tablet and for screen. We will see what is the concept, the 
foundation of it.<br>

In earlier days, It used to be a manual work that every single time you had to write CSS for mobile phones, for tablet screen and for the big screens and 
have to make everything pixel perfect. Now It is not that case. Nobody has the time or patience to just sit and watch one page being designed in 7-10 days.
Now people like to use advantages and some precooked in libraries and frameworks that can make this life so much easier. But still core foundation is exactly same
the way you work on those frameworks and libraries is also related to this. The foundation is still same. But those frameworks take care that things look out of the box
beautiful and It's much more faster and you will see the speed that how fast we can actuallty write CSS using those tools and frameworks.<br>
One of them is **Tailwind**.<br>

Here we will see only about 
- How the Breakpoint behave?
- How to read the breakpoints?

- ``` max-width: 1200px;``` max-width that after this point it's not going to be expanding further. It will stretch only 1200px beyond that it doesn't expand further.
  
- ``` min-width: 600px;``` **max** means that the maximum i can do, **min** means I require minimum this much to work
  
- We want to make Mobile responsive, especially we want to work on How does the responsive design works?
  - Whenever we work with the mobile responsive device, we have to provide some **media queries**
  - These media queries are nothing, they're annoted symbols which specifically mention that **Hey, what do you want to happen on a certain pixel size?**
  - Inspect your style in DevTool > Screen Tab > Responsive to see the pixel

- Now we have to find out a way through which we can tell our CSS that Hey, we want you to have a specific instruction on 600px or less than 600px.
So, How can we do that?
  - It's very easy in CSS itself you first use ```@media``` @ sign and you will see so many annotators, media alone doesn't work bcuz it's a way to tell that
    I want you to do something on this breakpoint, this particular pixe; breakpoint. If you're not going to provide that breakpoint, it doesn't work.
```html
        @media (max-width: 600px){
            body {
                align-item: flex-start;
            }
            .responsive-div {
                  background-color: Yellow;
            }
       }
```
  - you have to mentioned where you want this behaviour bcuz Now this @master{} is considered as whole CSS. So you have to mentione where you want to appear this.
    so apply this to your reponsive div.
  - body will take all rest of the things as it is but we will overwrite only certain property which is align-item: flex start, So on mobile devices
    we want this banner to be top with blue color and on the rest of the bigger screen devices we want it be on center. So, You have to be very precise and strategize how
    you want it to be behaving.
  - one good thing about these media query is they actually take all the things from here. So original design or the big web design, they actually transfers all of them
    as it is. But whatever you want to overwrite just have to work on overwrite. So It's not like we're writting CSS from the scratch on its own.

  - Now let's work for Tablet screen:
    - Again same ,media query, provide the breakpoint and then design elements whatever the element we want to target.

```html
    @media (min-width: 601px) and (max-width: 1024px) {
            body {
              align-items: center;
            }
            .responsive-div {
              background-color: hsl(0, 89%, 47%);
            }
          }
```

  - Minimun I required is 601px and Max I will stretch is till 1024px beyond that I will not handle.
  - The best way to test the behavior is Inspect and via point goes to responsive design.
  - Once you define your breakpoint you start working on the views that you want, you want to hide certain elements on the mobile screen. You go ahead and take, select
    those classes, set the display properties to none if you want. you don't want text is pretty big, you want the smaller text.Select the text element reduce the font
    and on bigger screen it automatics becomes bigger.

- This is the basics of How the breakpoint works and there is nothing more than that.

- The common question that comes around is - How will I know that It's 600px or 500px for mobile screen? How can we found out? It looks mobilsh but hey Mobile can be
  mobile can be this big or or that big? How will I know of that?
   - Usually such information is actually available to you but turns out the world has already done a lot of research. You don't have to do it?
   - [Tailwind CSS](https://v1.tailwindcss.com/docs/breakpoints)
   - They also have these breakpoints and they also do exactly same but actually they hide a lot of information from you so that you can start working and you don't
     have to worry. What Tailwind does is It provides you all thesebreakpoints automatically so that you can target the smaller devices, the medium devices,
     the larger devices or even the bigger devices and even 2xl ultra big devices.
  - So  this is what framework and libraries allows you to do. Once you know the basics on your own.

> You don't have to re-write and re-invent the wheel. This is already been done and researched. You focus on building the stuff.

- **This is your Responsive Design Basics and masterclass on breakpoint. Now you can design any webpage and change the behavior however you like or want.**

> Definately that's require a thorough planning,that's why there is usually a designer which gives you the exact look and feel of the website on the mobile device
and exact look and feel for bigger devices. That's where you start writing your code and start behaving that. 

---
