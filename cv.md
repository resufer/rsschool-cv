# Nikolai Sosnin

# Contacts:
* Mail - Oesterd@yandex.ru

# About Me:
23 years old, secondary education. I wish to become a specialist in what I like. My strengths:
1. Curiosity && Curiosity && Curiosity
2. Fast learning
3. Hard work
4. Purposefulness

# My skills:
+ JS, TS
+ HTML && CSS(SCSS)
+ React, Redux
+ Git
+ Node

# Sample Code:
```javascript
  
const snail = function (arr, result = []) {
  if (arr.length < 1) return result;

  if (arr.length === 1) {
    result = result.concat(arr[0])
    return result;
  } else {
    for (let l = 0; l < arr[0].length; l++) {
      result.push(arr[0][l]);
    }; arr.splice(0, 1);

    for (let i = 0; i < arr.length - 1; i++) {
      result.push(arr[i][arr[i].length - 1]);
      arr[i] = arr[i].slice(0, arr[i].length - 1);
    };

    for (let j = arr[arr.length - 1].length - 1; j >= 0; j--) {
      result.push(arr[arr.length - 1][j]);
    }; arr.splice(arr.length - 1, 1);

    for (let k = arr.length - 1; k >= 0; k--) {
      result.push(arr[k][0]);
      arr[k] = arr[k].slice(1);
    };
    return snail(arr, result);
  }
}
```

# Work experience:
+ Tripper - five months

# Education:
+ Youtube
+ Codewars
+ Leetcode
+ Books

# English level:
A1, studying in progress
