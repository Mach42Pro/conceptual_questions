# Mach42 Code Mini-Challenge 5/30/2020

# Suggestions:
We're not looking for an essay for these questions, a few sentences will do the trick. However, the more you're able to show command over the question the better. There's no word limit or anything, so just write as much as you need to answer the question thoroughly. You're not expected to write any code, so even for questions that involve code, please do not write any code. 

You're free to google to your heart's desire. Questions aren't weighted or anything, so answer as many as you can. We recommend that you pace yourself. It might be worth reading through all of the questions first before starting to get a good sense as to how you want to allocate your time. 


# Questions
You will have approximately 30 minutes to answer the following questions:

1. Assume you're starting a new React/Angular application. How would you determine if a particular piece of code should be made into a component or not? (Worded differently: For an particular snippet of code in a react application, what considerations would you make before converting it into its own component?) <br/><br/>
Your Answer:<br/>
<strong>I would start by creating a wireframe of the site, and I would define components if there are sections that can be used on other pages or later in the code.</strong>
<br/><br/>
<br/><br/>

2. Briefly explain what time and space complexity are in development. Why are they valuable to measure and how would one measure them?<br/><br/>
Your Answer:<br/>
<strong>Time and space complexities are ways to see how effecient a code is.  They are valuable because depending on the organization, you can lean more on speed or memory.  Time and space can be measured using BigO Notation.  Both use the inputs of the code and how it affects the overall result as the size of the inputs increase.  </strong>
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
<strong>The reverse function is never called or a scope issue.  Just trying to put something down here.</strong>
<br/><br/>
<br/><br/>

4. Imagine you're running a web development freelance operation. A client asks you to build them a website. Assuming they are 100% non-technical, how would you determine what technologies to use to build the application? (Yes, this is inherently incredibly vague).<br/><br/>
Your Answer:<br/>
<strong>I would ask them who are they planning on hiring or assigning to be in charge of the website.  Then depending on technical expertise of that individual, that would determine using a CMS like wordpress or using code that will last a while like react. </strong>
<br/><br/>
<br/><br/>

5. Briefly describe the 'seperation of concerns' in development (ex: Why we separate HTML, CSS, JS). Why is this important? How do you determine when things should be broken down and separated? <br/><br/>
Your Answer: <br/>
<strong>I believe structure determines the separation.  You can't have CSS without HTML, etc.  The decision to separate depends on how large the impact would be.  If there are many libraries, commands, etc, make it stand alone.</strong>
<br/><br/>
<br/><br/>

# Instructions for Submission:
Fork and Clone this repo onto YOUR github account of choice.
Submissions should be in the form of a Pull Request with YOUR NAME in the title (ie: Luke Skywalker - Mach42 5/30/20 Code Mini-Challenge).

