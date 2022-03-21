# Komarova Irina


## Contacts:
* discord: Irina Komarova (@kmrvais)
* telegram: @kmrvais


## About Me:
I have experience as a front-end developer in a small team. The goal of my training is 
to grow into a front-end engineer, gain more knowledge of JS and frameworks.


## Skills:
* HTML, CSS, Sass, BEM
* JavaScript Basics
* Adobe Photoshop, Figma
* Git
* PHPStorm


## Code example
Find the odd int (Kata codewars):
Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times.
```
function findOdd(A) {
  
  while (A.length > 1) {
    let hasNotCouple = true;
    for (let i = 1; i < A.length; i++) {
      if (A[0] === A[i]) {
        hasNotCouple = false;
        A.splice(i, 1)
        A.splice(0, 1);
        break
      } 
    }
    if (hasNotCouple) {
      return A[0]
    }
  }
  return A[0]
}
```


## Work experience
I have experience as a front-end developer.

educational project: [https://github.com/kmrvais/els-test.git](https://github.com/kmrvais/els-test.git)


## Education
Russia, Amur State University, Department of Mathematics and Computer Science

Сourse learn.javascript.ru - JavaScript/​DOM/​Interfaces


## English
A2


