# Kazus Anastasiia

## Contacts:
* e-mail: kazus0105@mail.ru
* phone: +(995) 551-558-941
* github: [AKazus](https://github.com/AKazus)

## Summary:

## Skills:
* HTML, CSS
* JavaScript
* React JS
* Git
* VS Code

## Code examples:
[**Range Extraction**](https://www.codewars.com/kata/51ba717bb08c1cd60f00002f)

A format for expressing an ordered list of integers is to use a comma separated list of either individual integers or a range of integers denoted by the starting integer separated from the end integer in the range by a dash, '-'. The range includes all integers in the interval including both endpoints. It is not considered a range unless it spans at least 3 numbers. For example "12,13,15-17"
Complete the solution so that it takes a list of integers in increasing order and returns a correctly formatted string in the range format.

```js
function solution(list){
 let string = `${list[0]}`;
 let isInterval = 0;
 
  for (let i = 1; i < list.length; i++) {
    if (list[i-1]+1 != list[i]){
      if (isInterval) {
        if (isInterval == 1) {
             string += `,${list[i-1]}`;
        } else {
             string += `-${list[i-1]}`;
        }
      }
      string += `,${list[i]}`;
      isInterval = 0;
    } else {
      isInterval += 1;
      if (i == list.length-1){
        if (isInterval == 1) {
             string += `,${list[i]}`;
        } else {
             string += `-${list[i]}`;
        }
      } 
    }
  }
  return string;
}
```

## Education:

