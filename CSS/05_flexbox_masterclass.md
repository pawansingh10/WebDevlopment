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
