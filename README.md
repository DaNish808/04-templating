Lab 04: Templates
=======

## Learning Objectives
* Discuss different ways to reuse HTML, specifically using templates.
* Display data using a Handlebars template.
* Distinguish between the different Handlebars expression types ( **{{}}** vs **{{{}}}** ).
* Add personality to a website by styling the typography.
* Interpolate a variable into a string using ES2015 template literals.

---

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)
[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

---

## Feature Tasks  
1. Include the Handlebars.js file in your project.
1. Convert your existing template html code into a Handlebars template.
1. Update your article `.toHtml()` method to use Handlebars.
1. You may find it useful to attach some additional properties to your article object, before you hand it off to the template.
1. Ensure the proper use of template literals, when applicable. *No more string concatenation!*

#### Stretch Goals
1. Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it with.

---

## Submission Instructions
When you are finished with lab, follow these steps to submit your work. Create one Pull Request (aka: "PR") from your Forked repo to the CF repo with your changes, and you'll each submit that same PR link in Canvas.

1. Ensure that all your local changes are committed, and pushed to your origin repo.
1. Visit the origin repo on github.com, and ensure that all of your completed work has been merged to master via Pull Requests within your repo.
1. Create a new PR from your Fork to the CF repo and ensure the branches look correct.
1. Fill in the template based on the text box prompts:
  1. Write a good descriptive summary of your changes:
    1. Be sure to include how much time you spent on it, and who you worked with.
    1. Briefly reflect on and summarize your process.
1. When you create the PR, it will have a unique URL. Copy this link, share with your partner, and paste it into the assignment submission form in Canvas. Both the driver and the navigator will submit the same PR link.
---

## Rubric  
Criteria | Pts
---|---
Meets all Assignment Reqs | 6
Uses idiomatic code style | 3
Follows proper Git workflow | 1
**Total** | **10**
