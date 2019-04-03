# EZ-Layout
EZ-Layout is just a basic, light weight, and easy to use grid system for responsive websites. 

So, I'll get straight to the point. EZ-Layout has a maximum of 12 columns per row because I couldn't find reasoning to make it any more than it needed to be.

___

## Rows & Columns
At the most basic level, you have have rows and columns. Below, I made a single column with 12 being the size of it. The numbers range from 1-12. When you're laying everything out, make sure that the column sizes add up to 12.
```
<div class='row'>
    <div class='c-12'></div>
</div>
```
###### Please note that this system has no other styling than the grid system, so you still need to deal with spacing from within the columns.

## Contain the Elements
So you're probably wondering why the columns are so stretchy. Well, that's because I wanted things to be flexible. You can **_contain_** these columns by adding the class **_contain_**.
```
<div class='contain'>
    <div class='row'>
        <div class='c-12'></div>
    </div>
    <div class='row'>
        <div class='c-12'></div>
    </div>
</div>
```

## Responsive Columns
So most websites nowadays are viewed from a mobile device, so you're probably going to want to have some sort of responsive column thingamajig that can **_collapse_** when the screen size is small. All you have to do to make things mobile friendly is add the class **_collapse_**.
```
<div class='contain'>
    <div class='row collapse'>
        <div class='c-4'></div>
        <div class='c-4'></div>
        <div class='c-4'></div>
    </div>
</div>
```

### That's all!