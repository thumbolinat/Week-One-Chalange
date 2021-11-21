WEEK-ONE-CHALAGE

In this week challenge, we were provided already prepared HTML and CSS code and our assignment was to prepare the code refactor to meet the following criteria:
USER STORY
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines

Acceptance Criteria
GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

First thing that I have noticed is that the title was very descriptive. I have changed the title to reflect the company name.

Another thing that I have noticed was that not all of navigation components were coded to take the viewer to the correct section of the website. That was the next item that needed to be fixed. 
Next I have noticed that code contained endless div elements and it was hard at first look to determine where when one div begins and another one ends.  I have used different elements such as nav, section article to give the index.html more structured view and make it more readable. 
After some cleaning up, I have added made the images user friendly by implementing “alt” attribute. This part had given me some hard time as the descriptive text was still not activating on the website even though I have implemented  “alt” accordingly, After some online research, I have found a solution, but implementing “title” attribute as well. This has solved the problem. Example below

 alt="office desk" title="Office Desk" 


After index.html was sorted out. I have proceeded with CSS stylesheet.
There were number of repetitive elements so it made sense to group them as much as possible. 
I have tried doing the grouping by creating subclasses in index file, however that did not work as desired as for some reason it was constantly changing layout and some of parameters assigned in the stylesheet were not activating. 
Aster researching this topic, I found out that I can group then simply by listing each class divided by comes in style sheet followed by the code and that solved the problem.  Example below.

.benefit-lead h3, .benefit-brand h3, .benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;


Below is the browser view of the website

<img src= "./asssts/images/Website-Photo-1.jpg"/>

<img src= "./asssts/images/Website-Photo-2.png"/>

<img src= "./asssts/images/Website-Photo-3.png"/>