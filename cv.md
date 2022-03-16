# Komarova Irina
********* 
##Contacts:
* discord: Irina Komarova (@kmrvais)
* telegram: @kmrvais
********* 
##Skills:
* HTML, CSS, Sass
* JavaScript Basics
* Adobe Photoshop, Figma
* Git
********* 
##Code example
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
********* 

