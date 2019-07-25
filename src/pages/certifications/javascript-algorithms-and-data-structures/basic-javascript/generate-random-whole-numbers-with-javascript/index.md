---
title: Generate Random Whole Numbers with JavaScript
---
## Generate Random Whole Numbers with JavaScript

Use Math.random() to generate a random decimal.

Multiply that random decimal by 10.

Use another function, Math.floor() to round the number down to its nearest whole number.

Remember that Math.random() can never quite return a 1 and, because we're rounding down, it's impossible to actually get 10. This technique will give us a whole number between 0 and 9.

Putting everything together, this is what our code looks like:

return Math.floor(Math.random() * 10);

Basic Solution.

var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.
  
 return Math.floor(Math.random() * 10);
  
}

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/basic-javascript/generate-random-whole-numbers-with-javascript/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
