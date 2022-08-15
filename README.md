# horiseon-code-refactor

## Description
This repository is for the website Horiseon, which expains Search Engine Optimization ,Online Reputation Management and Social Media Marketing. 


Code refactor has been conducted to make the code easier to maintain.


The deployed website is https://ruxinqu.github.io/horiseon-code-refactor/
## Changes Made
#### HTML:
1. Changed the title to Horizon.
2. &lt;div&gt; changed to semantic elements like &lt;header&gt;&lt;nav&gt;&lt;main&gt;&lt;footer&gt;&lt;section&gt;&lt;aside&gt;.
3. Added alt attribute to non-decorative images.
4. Changed the footer heading to &lt;h4&gt;.
#### CSS:
5. Consolidated the three same styling on `.search-engine-optimization`, `.online-reputation-management` and `.social-media-marketing` under one class selector `.content-box`.
* Moved the same styling on `.search-engine-optimization img`, `.online-reputation-management img` and `.social-media-marketing img` to one selector `.content-box img`.
* Moved the same styling on `.search-engine-optimization h2`, `.online-reputation-management h2` and `.social-media-marketing h2` to one selector `.content-box h2`.
6. Consolidated the three same styling on `.benefit-lead`, `.benefit-brand` and `.benefit-cost` under one class selector `.benefit-box`.
* Moved the same styling on `.benefit-lead img`, `.benefit-brand img` and `.benefit-cost img` to one selector `.benefit-box img`.
* Moved the same styling on `.benefit-lead h3`, `.benefit-brand h3` and `.benefit-cost h3` to one selector `.benefit-box h3`.
7. Put all the same `font-family` in the `body` selector.
8. Consolidated the same styling on &lt;header&gt; and &lt;footer&gt;.
9. Added comments to separate different section in HTML and CSS file, so that it's organized and easier to maintain.

## Sources Referenced
[Google](https://www.google.com/) | [MDN web docs](https://developer.mozilla.org/) | [W3schools online web tutorials](https://www.w3schools.com) | [Codecademy](https://www.codecademy.com/learn)

## User Story
AS A marketing agency I WANT a codebase that follows accessibility standards 

SO THAT our own site is optimized for search engines.

## Acceptance Criteria
GIVEN a webpage meets accessibility standards

WHEN I view the source code

THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements

THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the image elements

THEN I find accessible alt attributes

WHEN I view the heading attributes

THEN they fall in sequential order

WHEN I view the title element

THEN I find a concise, descriptive title

## Mock -Up
The following image shows the web application's appearance:

![The website's apperance](./assets/images/01-html-css-git-homework-demo.png)



