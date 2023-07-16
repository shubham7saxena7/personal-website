---
title: "Eating in is expensive"
date: 2023-07-11T09:03:20-08:00
summary: "A quick swiggy expenditure analysis to discover personal eating habits"
tags: ["food", "finances"]
---

Recently I ordered juice, some oats and a fruit salad from my favourite eatery - "Saladspoint" in Gurgaon. They do serve some delicious and more importantly clean hygienic food. All of it cost me about 800 Rs. and add another 300 Rs. of my daily coffee which I order from Third Wave Coffee Roasters. All of this is quality, rich and tasty food - but above all it was **expensive.** I am an admirer of taste but I am also frugal. I remember how each of the items I own, eat or splurge on cost. I believe this is a part of my nurturing.

This led me to a rabbit hole of exploration - how much have I ordered in the last six months? Honestly, I was scared to know this number. The exploration was multipart

**See if Swiggy shows it to you directly - some analytics of how much you've ordered**

Nah! They don't do that here! The whole point of micro-spending is that you fail to see the big costs. It is like the EMIs, they make you forget how much you end up paying.

**Hacking on mobile app network requests**

could have done this but very limited experience with mobile app debugging held me back

**Our saviour - https://swiggy.in**

Fortunately for me, there is a web version of Swiggy which shows paginated orders in chunks of 5. That was not a problem, just had to find the parameter for pagination and I had my order history in JSON! bam! you can check this [blog](https://towardsdatascience.com/midnight-hack-episode-1-visualizing-my-swiggy-order-history-f1cce25cbff6) on how to do this.

### The results

I just used Python to calculate and visualise the data. also, the script was written by our saviour - chat-gpt.

![](/images/order-per-month-cumulative.png)

I ended up spending north of 1 lakh Rs. in orders just from "food", i.e. close to an average of 600 Rs a day.

**My coffee addiction**

![](/images/order-coffee-cumulative.png)

I've spent closer to 18000 rs in the last six months on coffees ordered from outside, i.e. 3000 Rs. a month and 100 Rs. daily.

**My salads and oats problem**

![](/images/order-salad-cumulative.png)

I've spent close to 32000 Rs on oats and salads and that I feel is a shame. Both of them are pretty basic to cook and can be freshly prepared. I've just been a lazy bum!

### My Learnings and Actionable

* Cut down order amount by at least 50% in the next six months
    
* I'll be using the remaining 50% to purchase equipment and raw materials - maybe a coffee machine, good coffee, oats, vegetables, fruits and dressings.
    
* It is always good to know your spending habits. They act as feedback whenever you're about to spend next and optimise for the future
    
* Eating healthy is not expensive. We just make it to be.