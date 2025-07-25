## 💪 Flexbox Masterclass

If we introduced with flexbox all the properties at start all feel boring.<br>
that's wht we introduce flexbox in just one or two ways like especially in building up navigation bar it's digestable otherwise it's too lengthy there're lot of properties.<br>
 
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

## 💪 Grid Masterclass
Here, we will learn to bring out any layout to the life that you really imagined.<br>
You don't need any other resourse outside this discussion.

- We will see Different kind of layout and try to build them up
- By the way Grids are all responsive, they can stretch on the all type of screen small or big
- We will see some CSS tricks as well
- HTML file is pretty basics, every single time we have container( ```<div class="conatiner">```), inside the container we can have heading ```<h2></h2>``` then another container(```<div class="grid-container"```) and inside that each of the box gets label as box(```<div class="box"```)
- We can give them color using CSS logic, in the box we can select n'th child using that filling bg color to even boxes.<br>
  Iterating over nth child and manipulating its color.
```html
<style>
.box :nth-child(even){
      background-color:#ef74c3c;
  }
</style>
```
- Every conatiner gets a ```display: grid;``` without applying the property of display grid, it doesn't behave like a grid. but we're not using any other properties
  neither the template for rows nor template for column nothing like that. we will code them as we go along.<br>
  
1. Basic Grid of 3X3 : You will will using this like anything 2X2 3X4 etc<br> 
Here, we want rows to be 3 and columns to be 3. So we know that grid-template-column and grid-template-rows can achieve that and also we have seen repeat(3,1fr) property or 1fr 1fr,1fr.<br>
a) Say Hi to ```<div class="grid-conatiner" style="grid-template-columns: repeat(3,1fr)" ></div>```<br>
grid-template-rows: repeat(3, 100px); Hey, If it's repeat upto 3 columns each of the column should get 100px.<br>
```html
<div class="container">
      <h2>1. Basic Grid (3x3)</h2>
      <div
        class="grid-container"
        style="
          grid-template-columns: repeat(3, 1fr);
          grid-template-rows: repeat(3, 100px);
        "
      >
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box">5</div>
        <div class="box">6</div>
        <div class="box">7</div>
        <div class="box">8</div>
        <div class="box">9</div>
      </div>
    </div>
```
2. Grid with different column size : You will also used this anything especially on mobile layout<br>
Here, we want to apply grid to control columns, If we want to make second column big.<br>
We can say Hey style, I want to control the column so grid-template-columns and provide fraction as we know exactly there are three of them so 1fr 2fr 1fr.
This is usually know as Twitter style layout where we have 1fr 2fr 1fr, center one gets timeline, you can build so many of the social media just with this.
To put navigation bar, suggestion in the each sides and all the feed goes up in the middle.
```html
<div class="container">
      <h2>2. Grid with Different Column Sizes</h2>
      <div class="grid-container" style="grid-template-columns: 1fr 2fr 1fr">
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
      </div>
    </div>
```

3. Grid with Gaps : Just meant to show gap is if you want to consume them<br>
Here, we will be controlling the gap as well as provide the columns, not worry about row rows can be as it is.
Hey style, I want to control the grid-template-columns, repeat for 3 of the columns 1 fraction each. and also we want to control gaps, already gaps are there because
of margin property being applied on them. But we can control gap further. So put ```gap: 20px``` <br>
```html
<div class="container">
      <h2>3. Grid with Gaps</h2>
      <div
        class="grid-container"
        style="grid-template-columns: repeat(3, 1fr); gap: 20px"
      >
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box">5</div>
        <div class="box">6</div>
      </div>
    </div>
```
<br>
4. Grid item Placement : Used in Rare cases like Gallery, Blockpost, crazy cards or bento box<br>
Here suppose we want 3 columns and each takes 1fr that's already we have see control it from grid container, 

```html
<div
        class="grid-container"
        style="
          grid-template-columns: repeat(3, 1fr);
          grid-template-rows: repeat(3, 100px);
        "
      >
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box">5</div>
      </div>
    </div>
```
now we want the first column to consume more spaces specifically. The 1st box is there we want to consume more of the elements
So Let's say add a style and grid-column, how many columns you're going to consume, Let's say you start with first and move it up to the three ```style="grid-column: 1/3"```<br>
```html
<div class="container">
      <h2>4. Grid Item Placement</h2>
      <div
        class="grid-container"
        style="
          grid-template-columns: repeat(3, 1fr);
          grid-template-rows: repeat(3, 100px);
        "
      >
        <div class="box" style="grid-column: 1/3; grid-row: 1/3">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box" style="grid-column: 2/4">5</div>
      </div>
    </div>
```
5. Grid Template Area : Shows you how much power you can have if you can define the architecture or layout of your page on top lavel, this can achieve nicely and it maintains the layout even on the smaller screen.<br>
It's interesting, It's bit of a complex work but grid make it super easy to work with.<br>
Here, we don't have 1,2,3 rather we have Header, Sidebar, Main Content and Footer. So, the Goal is Header usually takes from left to right, the whole element.<br>
The sidebar usually takes one of the fraction and the main content takes bigger fraction abd footer also goes all the way from left to right.<br>
We can achieve this easily by designing it into three column layout.<br>
What we can do is in each of these headers,sidebar,main ad footer inject a style and each element has its name. ```grid-area:``` property this determines the location this is like linking that what did I name you so that I can control you from parent element.
```html
        <div class="box" style="grid-area: header">Header</div>
        <div class="box" style="grid-area: sidebar">Sidebar</div>
        <div class="box" style="grid-area: main">Main Content</div>
        <div class="box" style="grid-area: footer">Footer</div>
```
<br> Now we want to control grid-template area that how the template area will look like. So we will go up to the parent and will say I want to inject a style.
Now, another interesting way of Having grid template areas. **Each element is called as area, singular that means each child will get area** and **Whole parent is called as areas, plural that means It's for Parent**<br>
Now we want that column, we will use 3 columns so will be designing 3 of them. or basically we will say 3 rows 1st row goes for the header, 2nd rows goes for main and side bars and 3rd rows goes for footer.
```style="grid-template-areas: 'header header header` 'sidebar main main' 'footer footer footer';"``` 
1st portion of it is going to be control by header and  2nd and 3rd also going to be header.<br>
2nd portion is going to be controlled sidebar, 2nd main 3rd main<br>
3rd portion all is going to be control by footer.<br>

This way you can ctually allocate more to the content ```style="grid-template-areas: 'header header header header` 'sidebar main main main' 'footer footer footer footer';"``` Now everything is divided into 4 fractions, 1 fraction to side bar and 3 fractions to main content.Header and footer gets all of it.<br>
You have to be very precisely mentioning all these grid area, you can't just do any changes and mess it up.

```html
<div class="container">
      <h2>5. Grid Template Areas</h2>
      <div
        class="grid-container"
        style="
          grid-template-areas: 'header header header header' 'sidebar main main main' ' footer footer footer footer';
        "
      >
        <div class="box" style="grid-area: header">Header</div>
        <div class="box" style="grid-area: sidebar">Sidebar</div>
        <div class="box" style="grid-area: main">Main Content</div>
        <div class="box" style="grid-area: footer">Footer</div>
      </div>
    </div>

```
6. Auto-fit and Minmax : They behave like flexwrap<br>
This is bit of inspired by **Flexwrap**. This can be control by parent as well, go to the parent and inject style="grid-template-columns: repeat()"
Till now, we're giving numbers like 3 columns each getting 1fr but What if we have no idea how many elements are going to come up? For that there is an option which say ```repeat(auto-fit, minmax(100px, 1fr))``` and it will automatically try to fit it but another property needs to be given for that is tell me what could be minmax size?
Magic happens when if the space gets shrink and nobody is able to get min of 100px, that exactly the point they will pushed onto the next row and the next row also will have 100px and it will keep on going. Almost lika a flexwrap.
```html
<div class="container">
      <h2>6. Auto-Fit and Minmax</h2>
      <div
        class="grid-container"
        style="grid-template-columns: repeat(auto-fit, minmax(100px, 1fr))"
      >
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
        <div class="box">4</div>
        <div class="box">5</div>
        <div class="box">6</div>
      </div>
    </div>
```
7. Alignment and Justification<br>
Again grid-template-columns: repeat(3,1fr);, now we have alignment and all of them. Now turn out you can actually go ahead and use other properties here as well within the grid. What can we use here? ```justify-content: space-between; align-item: center;``` In order to show you this effect, we need to first give the height.

```html
 <div class="container">
      <h2>7. Alignment and Justification</h2>
      <div
        class="grid-container"
        style="
          grid-template-columns: repeat(3, 1fr);
          height: 200px;

          align-items: center;
        "
      >
        <div class="box">1</div>
        <div class="box">2</div>
        <div class="box">3</div>
      </div>
    </div>
```

8. Nested Grid : You may used this<br>
We have grid container inside that we have further a grid container. inside that we have more elements 2.1 2.2 2.3 2.4 <br>
First we have to see outer container as one grid<br>
Then See the inner container as one grid under which we have elements 2.1 2.2 2.3 2.4
```html
<div class="container">
      <h2>8. Nested Grids</h2>
      <div class="grid-container" style="grid-template-columns: 1fr 1fr">
        <div class="box">1</div>
        <div class="grid-container" style="grid-template-columns: 1fr 1fr">
          <div class="box" style="background-color: #27ae60">2.1</div>
          <div class="box" style="background-color: #27ae60">2.2</div>
          <div class="box" style="background-color: #27ae60">2.3</div>
          <div class="box" style="background-color: #27ae60">2.4</div>
        </div>
      </div>
    </div>
```

9. Grid with Auto Rows : rarely used<br>
First repeat them into 3 columns so style="grid-template-columns: repeat(3,1fr)" now you can se is that one of the column is taking too much because it's having too much of content and bcuz grid is smart enough to actually don't push your layout  rather it's automatically trying to strech others columns so that they were equal height. This is good but you want to control the height as well. **Heights are being control as how much rows you're consuming.**<br>
Another properties you can use is ```system="grid-auto-rows: minmax(100px,auto)"``` or ```system="grid-auto-columns"```, all we got to do is min max.

- **Bento box design**, these days every cards look like these bento, which used to be lunchbox in japan. you will these pattern on apple website.

> 🔴 **In the world of CSS, there is a never ending learning process, People spends 5-6 years more in just understanding each property and preparing a nice display**

> 🟢 But the idea is not to go in hunt of learning everything at once, you don't need it. you will need whatever you need, figure it out and start building the project. That's the only best way to learn.

> Once you are confident in building the outer layout, putting the content inside in it is no big deal. Everybody can do that.🙂

---

