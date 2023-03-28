# Denis Akhmarov
# Contacts
* tel: +79193659090
* github: denisakhmarov
# About me
Student of Rolling Scope School. 36 years old. I want to dive into the world of coding. 
# Skills
not yet, but this field will be filled soon, I promise
# Code example
<details>
  <summary>Задание</summary>
  If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).
Note: If the number is a multiple of both 3 and 5, only count it once.
</details>

```
function solution(number){
   if (number < 0) {
    return 0;
  } else {
    let multiples = [];
    for (let i = 0; i < number; i++) {
      if (i % 3 == 0 || i % 5 == 0) {
        multiples.push(i);
      }
    }
    new Set(multiples)
    let result = multiples.reduce((sum, current) => sum + current, 0);
    return result;
  }
}
```
# Experience
and this later
# Education
Ural Federal University 2010-2015
