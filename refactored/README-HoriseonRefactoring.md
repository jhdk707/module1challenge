
Project: HORISEON Website Re-Factoring 12/3/2022
Completed by JESSE HUDAK for UCB Extension Coding Bootcamp


## User Story (As Documented in the Source Files for this project)

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria (As Documented in the Source Files for this project)

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Challenges 

This was my first time attempting to clean up HTML or CSS code. I spent a large amount of time researching semantics in-depth, went back and watched the Zoom for class to re-watch what Mark Carlson was teaching us and started to get things to click. 

I spent a good part of the day messing around with tags and seeing what would break the site, what worked, what changed formatting if things were moved around and consolidating CSS class and style codes. The part I had the hardest time with was the NAV bar, the original layout had a couple DIV tags that kept changing the display:line-block code for it back into bullet points. 

This went on for a while until I looked more closely at the CSS Code and noticed ".header div ul li" line and figured that when I changed DIV to NAV or whatver, that CSS line would break. I changed ".header div ul li" to ".header nav ul li" and things started working. Any other related code attached to DIV was changed to NAV, made comments, tested and it worked! 

## Resources Used 

https://www.w3schools.com/html/html5_semantic_elements.asp 
 - I found this website during the pre-work and it has been very helpful as a reference and instructable on things that I have been stuck on or unfamiliar with. 

https://www.youtube.com/watch?v=kX3TfdUqpuU&t=754s
  - This video helped me understand semantics a little better visually as it was being done live and gave me some ideas on how to fix issues I was having

https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
 - This page I referenced all my work to after I felt like I had cleaned things up enough to be considered ready for review 

 ## Personal review

 One thing that I was having issues with was using terminal for git pull/push/add, I still need some practice. I got a couple commits to go through with messages, however most were pushed through VSCode and I did not figure out how to do commit messages until the very end, so I know I will be lacking some commit messages in the REPO for this project. I will continue to practice more with terminal to understand how to use it better 