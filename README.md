# BEM Notation

A project on how to write scaleable CSS using BEM notation.

## What is BEM? 🧐

BEM notation is a CSS naming convention designed to keep CSS understandable, scaleable and avoids naming conflicts and specificity wars. Creating "Blocks" keeps code modular and re-usable, reducing the amount of code you have to write. Yay.

BEM stands for Block Element Modifier and has a high adoption rate amongst developers due to it's low cost, ease of use - and success!

Lets break it down...

![B-b-break it down!](./break-dance.png)

## Block

A "Block" is a standalone entity that is meaningful on it's own.

Some "Block" examples might be: buttons, headers, containers, cards, list and input 


## Element 

An "Element" is part of a block. An element has no meaning on it's own.

For example, some "Elements" would be: button text, header title, list item, container card. 

Each element belongs to it's block parent. A header's title. A list's item etc. 

A double underscore __ means inside the block


## Modifier

A "Modifier" changes - or modifies 😉 - a block or elements appearance or behaviour.

For example, some "Modifiers" might be: disabled, on/off, size small, color red etc

Double hyphen -- signals a modifier.

------

Heres an example in code:

```
Block component
.button {}

Element that depends upon the block
.button__text {}

Modifier that changes the style of the block or element
.button--red {} 
.button--small {}

Used together they might look something like this:
.button__text--red
```

## BEM in Practice 👩‍🎨

Now you're down with kids and understand what BEM is, it's time to put those sweet new learnings into practice!

After forking this repository you will need to then clone the repo locally and open up your index.html file in the browser.

Type 'open index.html' in your terminal and press enter (make sure you're in the right directory!). Your Star Wars / BEM wars page should open in your browser. Alternatively, right click on your index.html file and select 'open with..' then select the browser of your choice.

You should now see pictures of Darth Vader and Yoda on your screen, yes you will. 

## The Challenge 🤺

The internet is being destroyed by unscaleable, unmanageable CSS! Specificity wars are everywhere, elements are lost in the deep dark depths of nesting and fleets of developers are feeing for their lives! But!

Rebellions are built on hope... and a little more knowledge around BEM lights our way.

In your index.html file you must work with ~~Yoda~~ BEM to create a more manageable, more zen web page.

## The Rulez 😒

Your page should:

- Have two cards, one light coloured card for Yoda, The Force and BEM. One dark coloured card for Darth Vader and his CSS hell!

- Have some card styling like borders, padding, shadows etc

- Use BEM notation to clearly name and structure your CSS to target block, elements and modifiers on the page

* * Hint: avoid duplication in your code. Remember your block styles will affect all cards whereas your modifier styles will change specific, or individual things like the *colour* of your cards.

- NOT use Ids (this is because BEM recommends avoiding Ids and only using classes to avoid specificity wars)


## Extension 🔥

- Using flexbox make your cards sit side by side, in the middle of the page

- Add more cards with the same base styles of The Dark and The Force cards but with different colours and images
