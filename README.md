# Mach42 Code Mini-Challenge 5/30/2020

# Suggestions:
We're not looking for an essay for these questions, a few sentences will do the trick. However, the more you're able to show command over the question the better. There's no word limit or anything, so just write as much as you need to answer the question thoroughly. You're not expected to write any code, so even for questions that involve code, please do not write any code. 

You're free to google to your heart's desire. Questions aren't weighted or anything, so answer as many as you can. We recommend that you pace yourself. It might be worth reading through all of the questions first before starting to get a good sense as to how you want to allocate your time. 


# Questions
You will have approximately 30 minutes to answer the following questions:

1. Assume you're starting a new React/Angular application. How would you determine if a particular piece of code should be made into a component or not? (Worded differently: For an particular snippet of code in a react application, what considerations would you make before converting it into its own component?) <br/><br/>
Your Answer:<br/>
<strong>YOUR ANSWER GOES HERE</strong>
<br/><br/>
So the rule of thumb when it comes to components is that each component should roughly have one job. So while you are building out your app, if you realize that you have multiple chuncks of code providing multiple functions, or having different jobs, I would suggest you break that chunk of code up and put it into separate components. You could also discern if you should put a chunk of code in a component if you plan, or intend to use that chunk of code multipule times. Having one component to refer to instead of having duplicates of that same chunk of code is definitley the way to go :) 
<br/><br/>

2. Briefly explain what time and space complexity are in development. Why are they valuable to measure and how would one measure them?<br/><br/>
Your Answer:<br/>
<strong>YOUR ANSWER GOES HERE</strong>
<br/><br/>
Simply put, time & space complexity refer to how long it will take for your app to perform it's functions & how much space your data/app will need as it grows. You want to be able to measure your time & space complexity because they could potentially cost you a lot of money & significatly impact your apps performance.
<br/><br/>

3. You're given the snippet of code below that accepts a number as a parameter and returns the reverse of that number (i.e. INPUT = 123; OUTPUT = 321. However, this code is returning an error. Please describe why the code does not work and how you would fix it. <br/>
```
var reverse = function(x) {
  const y = x
    .split("")
    .reverse()
    .join("");
  return y;
};
```
<br/>
Your Answer:<br/>
<strong>YOUR ANSWER GOES HERE</strong>
<br/><br/>
So what I would suggest is, yes store the paramater in const y, but then specify that you want to split, reverse, and join the contents held in the const y.
<br/><br/>

4. Imagine you're running a web development freelance operation. A client asks you to build them a website. Assuming they are 100% non-technical, how would you determine what technologies to use to build the application? (Yes, this is inherently incredibly vague).<br/><br/>
Your Answer:<br/>
<strong>YOUR ANSWER GOES HERE</strong>
<br/><br/>
Well first I would ask them what they want to use their website for & how much they would like to be able to 'interact' with their website in the future without having to contact me to write up some code for them. For example, say they want to add another page for some new service they are providing - do they want to be able to do that themselves or would they perfer to just have me do it? If they chose the first option, I would suggest we build something involving a cms system of some sort. To decide which cms system to go for I would revert to their answer to the first question I asked - what they want to be able to do with their webiste. Blog? Do they need a store? Are they looking for a portfolio site..? If they want me to handle everything for them, I would probably suggest react, but I would need to ask more questions to see if they need a backend and whether they will be collecting data and how consistent that data will need to be. 
<br/><br/>

5. Briefly describe the 'seperation of concerns' in development (ex: Why we separate HTML, CSS, JS). Why is this important? How do you determine when things should be broken down and separated? <br/><br/>
Your Answer: <br/>
<strong>YOUR ANSWER GOES HERE</strong>
<br/><br/>
I believe this is sort of like the components question. We want everything to have one basic, fundamental 'job'. This makes debugging easier & it also makes the code more organized and easier to understand. I believe.. 
<br/><br/>

# Instructions for Submission:
Fork and Clone this repo onto YOUR github account of choice.
Submissions should be in the form of a Pull Request with YOUR NAME in the title (ie: Luke Skywalker - Mach42 5/30/20 Code Mini-Challenge).

