## 💪 Flexbox Masterclass

If we introduced with flexbox all the properties at start all feel boring.<br>
that's we introduce flexbox in just one or two ways like especially in building up navigation bar it's digestable otherwise it's too lengthy there're lot of properties.<br>
 
 Now we can learn Flexbox<br>
Here we will learn about flexbox and everything we can possibly do.<br>
Flexbox is really awesome and common even if you plan to go on mobile development later on a lot of things use Flexbox, especially the react native world<br>

But here our focus is to learn basics of it.

When we go with Flexbox there're 2 concepts that we need to remember in our mind
1. **Main axis**<br>
2. Other axis It is known by varieties of name like **Alternative axis**<br>

In the world of web, whenever you says Flexbox that means the main axis is going to run from left to right, yes It's horizontal bar and the reason for that is 
some of the properties are attached to the main axis and some of the properties are attached to the other axis.<br>
When you go into future and if you work on Mobile App the main axis actually changes from Top to bottom.<br>

We can style  through style attribute from the element itself also
```html
<div class="flex-container" style="flex-direction: column;">
    <div class="circle paster-1">1</div>
    <div class="circle paster-2">2</div>
    <div class="circle paster-3">3</div>
</div>
```
Justifying content - There're couple of other properties which starts with justify. This whole thing Justify actually runs on the main axis.
So It controls how your element are going to behave from left to right. The proportion is always left to right.<br>

Other one the Align-item or anything that starts with align, that controls the top to bottom axis or other axis.<br>

```html
Flex Wrap: wrap; // awhen we have many cards on the screen and we want to fit them on one row and on mobile screen automatically moves to next line just one line of css does the job. 
Flex Wrap: wrap; height: auto; //it doesn't tak too much of the extra white space in the container.
```
> We mostly used align-items and justify content. It does the job. another we use is flex wrap.

- Properties are actually assigned on a bigger container, whatever child is inside we actually don't control them directly. We don't put any CSS on those child.
  We actually worry just about those containers and control the behavior of the child through that container. That's the whole job of the flexbox and that's why flexbox was designed initially.<br>
But after sometime people realized that It's CSS, It always need more. So what we can do is control some of these inner elements exlicitly if you have the flexbox properties It doesn't work otherwise it needs to be with flex properties.

  
---


## 📄Meet grid layout in CSS - You will love it

Let's learn Grid, **Grid** is another way HOw you can layout elements on your webpage.<br>
We have already seen flexbox is completely capable of placing any element anywhere that you want. You're already a big fan og flex wrap which does alot of things for us.
In last few years we're forced to build one layout through the **grid** only. Yes, that's requirement of the job.<br>
The moment you started to understand the Grid, after that you will never look back.<br>
You will be now officially Grid fan. That's how it happens, you change the Tech, you change preferences over the time. May be after 5 years you'll love something else who knows?<br>

- What Grid is?
- What Basics of Grid is?
- Read docs
- Master Class on Grid to build multiple layouts, Power of Grid, How Grid behaves?

### Where to use FLEXBOX and where to use GRID?

> Still to this state, whenever We need to build any navigation bar we still prefer Flexbox because that makes much sense. The way most common laywout works in the
 navigation bar either everything is separated out like logo on one end and everything on another end. or divided into 3 parts where Logo on left, some-element on center. They can be easily distributed by the flexbox. So We can still prefer Flexbox in the navigation bar or navigation menu.

> But for rest of all the things We will prefer to have a Grid.
and some elements on the right.

You will see GRID more as row pattern, one row at a time. This is how visually we see the webpage, not the whole page at once. one thing at a time.<br>
Grid actually allows you to create really amazing patterns that can be introduced in blocks, images, Galleries even enitire webpage can be layout with it.<br>

- Let's start to work with grid
   - Now we want to put up some of the conatiners for the grid, the way how grid works is you have a parent container below that child or inside parent
     multiple child elements and goes on.
  - if you style edit with grid display: grid it does nothing unlike flex does something on own. this is bcuz there're 2 main requirement to be told to this grid first
    how many rows you wants and how many columns you want. SO you need to specify the rules that what's your expectation with the rows and columns. Usulally
    it starts with columns and columns goes from top to bottom **gtc-grid template column** **1fr** fr is a unit which means fraction that is automatically divides your page into 100% and then you just mentioned how much fraction you want to give to somebody. Let's say 3 guys then 1fr 1fr 1fr so each one of them gets equal fraction if you want to change it you can give 1fr 2fr 1 fr the width of the page is automatically calculated. Now you can see the page is divided into fractions
```html
.grid-container {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
      }
```
   - You can also control rows **gtr - grid-template-row**
```html
.grid-container {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: 100px 200px;
      }
```
  - property **gap: 20px** It actually introduces gap between each of these elements
  - ``` grid-template-columns: repeat(10,1fr);``` repeat keywords takes 2 things count and size

  - You can atually control the inner element at different level using grid, yes you can do that with flexbox as well. 
  - You can create amazing layout, Imagine you're building your cards, gallery images, Meduim style webpage to read articles to display images

  
---
