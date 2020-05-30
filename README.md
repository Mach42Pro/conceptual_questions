# Mach42 Code Mini-Challenge 5/30/2020

# Suggestions:
We're not looking for an essay for these questions, a few sentences will do the trick. However, the more you're able to show command over the question the better. There's no word limit or anything, so just write as much as you need to answer the question thoroughly. You're not expected to write any code, so even for questions that involve code, please do not write any code. 

You're free to google to your heart's desire. Questions aren't weighted or anything, so answer as many as you can. We recommend that you pace yourself. It might be worth reading through all of the questions first before starting to get a good sense as to how you want to allocate your time. 


# Questions
You will have approximately 30 minutes to answer the following questions:

1. Assume you're starting a new React/Angular application. How would you determine if a particular piece of code should be made into a component or not? (Worded differently: For an particular snippet of code in a react application, what considerations would you make before converting it into its own component?) <br/><br/>
Your Answer:<br/>

  If I were starting a React/Angular application, I would first roughly draw a diagram of what views and functions I need, and probably a wireframe too as it helps visually keep track of what the user would see and interact with. I would try to separate concerns, or what each component does, as much as possible.
  
  So for example, if I were using React Router, I would start with having each route be its own component. Then, for example, if I were writing a blog app, I would write a component that takes an individual blog post's data (title, content, author, etc) and displays it (in the way I want) so that the component could simply be reused.
  
  I've heard of examples where large component libraries are created for purposes such as styling (e.g. buttons, text boxes, input boxes, logos, nav bars, etc) so that a company or entity can reuse them and have uniformity and development convenience over a large app.
  
  The only consideration I have about writing components that are "too small" is that it clutters the file structure so maybe I would consider anything that doesn't do one job independent of other lines of code as too small. 

<br/><br/>
<br/><br/>

2. Briefly explain what time and space complexity are in development. Why are they valuable to measure and how would one measure them?<br/><br/>
Your Answer:<br/>

  Time and space complexity are how the time it takes to run the code, and the space in memory or storage required, scale as the input sizes increase. Big O notation is used to denote this. For example, if n is the number of data points in the input (usually the size of an array in some simpler examples), then O(n) means the time or space complexity scales linearly with n increasing. O(n^2) would mean the time or space complexity actually scales with n^2, so if n is doubled, the time or space complexity would actually quadruple. Time and space complexity can be calculated independent of each other and usually depend on the control flow and algorithm design.
  
  They are extremely valuable to measure in today's modern web development world because the more users use an app, the more the app designers/maintainers need to be concerned about how well their system can serve their users. For example, even if internet speeds are fast, if Facebook couldn't process your login and return your data quickly, you would have a bad user experience on Facebook. Also, if computations use a lot of wasted space, Facebook would have to spend multiples of their current expenditure on hardware to keep their app running.
  

<br/><br/>
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

 In Javascript, you can split a string but not a number. I'm assuming the parameter x is passed a number as an argument because Javascript doesn't strictly type the parameter. To fix this, I would change x to a string before running split, reverse and join. If necessary, I could also convert y to a number before returning.

<br/><br/>
<br/><br/>

4. Imagine you're running a web development freelance operation. A client asks you to build them a website. Assuming they are 100% non-technical, how would you determine what technologies to use to build the application? (Yes, this is inherently incredibly vague).<br/><br/>
Your Answer:<br/>
 
  If the client is 100% nontechnical, I feel that my best bet is to ask them to walk me through their desired typical user experience. For example, if I worked with a restaurant and they wanted a website, maybe they don't even need a backend because they could simply have their menu be static (HTML or PDF) and also print their phone number to order from. I think the role I would try to play is to turn vague directions into specifics. Some clients are inclined to answer specifically to questions immediately while others will ask us to design it, so I am looking to nail down the ABSOLUTE REQUIREMENTS first.
  
  A lot of interactivity on websites can be done purely with front-end, and many of them can probably be done in most technologies (vanilla JS, Angular, or React, and I know I'm not even listing close to everything). I would take into consideration what is easiest for me (and my team if I have one), who is maintaining it and what is easiest for them, and how often they would need to apply updates and if we need a system for the client to apply their own updates, such as through a browser CRUD tool.

<br/><br/>
<br/><br/>

5. Briefly describe the 'seperation of concerns' in development (ex: Why we separate HTML, CSS, JS). Why is this important? How do you determine when things should be broken down and separated? <br/><br/>
Your Answer: <br/>

  I mentioned separation of concerns in my answer to the components question, but in programming I think it applies to so many things (HTML, CSS, JS in web dev as well as how classes and functions are written in many different languages/applications). I think separation of concerns maps very well to good designs, which explain how parts of the app interact with each other. If we started a React app and did not draw wireframes or a component library, as it gets bigger we would just be slapping things on to connect to existing components.
  
  This has a lot of consequences for splitting up work for team members, expanding existing apps (both solo and team) and in maintaining these apps. For example, if my team member knows that they need to write a React component that takes a Javascript object containing the title, content and author of a blog post, it is a lot easier to design that separately than to have them start writing code into the file I'm already working on (and it would be reusable as well). Then, if our schema for the blog post changes (maybe the author changes from a string to an object that has the author_name and author_avatar image), then it is easy to go to the components that read the blog post object and specifically change those components.

<br/><br/>
<br/><br/>

# Instructions for Submission:
Fork and Clone this repo onto YOUR github account of choice.
Submissions should be in the form of a Pull Request with YOUR NAME in the title (ie: Luke Skywalker - Mach42 5/30/20 Code Mini-Challenge).

