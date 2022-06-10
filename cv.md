# Hi! I am Yuna Maiorova

*****
## My contacts:
* **Twitter:** Jatterai
* **Email:** maiorova.yuna@gmail.com
* **Github:** Jatterai
* **Telegram:** Jatterai

## About me
I'm going to be great Front-End Developer! But for now i'm on start of path. 

## Skills
* HTML
* CSS(SCSS)
* JavaScript _(beginner)_
* Photoshop
* Figma

## Code Example
This one from codewars(codewars.com)

>**Task:**
>Each letter of a word scores points according to its position in the alphabet: a = 1, b = 2, c = 3 etc.
>You need to return the highest scoring word as a string.
>If two words score the same, return the word that appears earliest in the original string.
>All letters will be lowercase and all inputs will be valid.

```
function high(x){
    let alphabet = 'abcdefghijklmnopqrstuvwxyz'.split('');
    const wordScoreCount = (word) => 
    word
    .split('')
    .map((letter) => alphabet.indexOf(letter)+1)
    .reduce((sum, letterScore) => sum + letterScore, 0);
    
    x = x.toLowerCase().split(' ');
    let xScores = x.map(wordScoreCount);
    
    return x[xScores.indexOf(Math.max(...xScores))];
}
```

## Work experiense

*place for my future experiences!*

## Courses and education

1. [FreeCodeCamp Responsive Web Design](https://www.freecodecamp.org/certification/jatterai/responsive-web-design)
2. JavaScript on [learnjavascript](https://learn.javascript.ru/)

## Languages

* Russian (native)
* English (intermediate)

