# Kazus Anastasiia

## Contacts:
* e-mail: kazus0105@mail.ru
* phone: +(995) 551-558-941
* github: [AKazus](https://github.com/AKazus)

## Summary:

Responsible and attentive metal structure designer with 5 years of experience. I decided to change the direction of my activity and move to front-end development. I am open to everything new, I am actively developing a new direction, I want to get into an IT company as a Junior Frontend Developer with the possibility of further development. I want to learn Front-End Development at RSSchool!

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
1. **Bachelor, Pacific National University**
   * Civil engineering and economy, 2011
2. **Master's degree, Pacific National University**
   * Builging Constractions, 2013
3. **FoxminED** 
4. **Hexlet** (in progress)
5. **RS-School** (in progress)  


## Languages: 
* Russian (native)
* English (A2)
