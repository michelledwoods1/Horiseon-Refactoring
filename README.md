# Horiseon Refactoring

## Description

I was tasked with refactoring a client's existing website code, in order to improve user accessiblity. 

Without changing the actions of the existing code, the codebase was **"cleaned"** to:
- meet accessibility standards ie. semantic HTML
- ensure code sustainability ie. relevant commenting, consolidated CSS and working Links


By following and meeting accessiblity standards, the client's website will now be:
- search engine optimised ie. rank higher
- accessible to people with disabilities (thereby avoiding possible litigation)

## What I learned
During the completion of this task, I learned:

- how to create and compose a valid README.md file using Markdown
- that the requirement to comprise a description in the README.md file is really a great opportunity to think about and comprehend what tasks are required
- how to correctly add a screen shot to the README.md file
- that <div> and class attributes are not necessary when an element aleady exists
- that <li> attributes need to show separately from <nav> attributes
- that <a> attributes in a list cannot be included in the <li> attributes of that list
- class selectors for images are linked to the parent class

## Steps Taken

#### Step 1 - HTML 1
Working from the top down, I looked for any obvious issues and found:
- Tiltle not very descriptive &mdash; changed from 'website' to 'Horiseon'
- Attritubues inserted between text of h1 name &mdash; corrected
- Images have unnecessary spacing at end of elements &mdash; corrected
- Paragraphs have uncessary spacing at start of sentences &mdash; corrected
- Footer has h2 header element &mdash;changed to h3

```
>To check purpose and relevance of <span> element
>To check relevance of multiple <div> elements
>Check line spacing within list elements

```

### Step 3 - CSS 1
- header has been created as a Class, but can be created using the element



 



![Screenshot of Webiste url](assets/images/screenshot.png)
## Installation
What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.
## Usage
Provide instructions and examples for use. Include screenshots as needed.
To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

## Credits
List your collaborators, if any, with links to their GitHub profiles.
If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.
If you followed tutorials, include links to those here as well.
## License
The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).
---
🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.
## Badges
![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)
Badges aren't necessary, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.
## Features
If your project has a lot of features, list them here.
## How to Contribute
If you created an application or package and would like other developers to contribute it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.
## Tests
Go the extra mile and write tests for your application. Then provide examples on how to run them here.