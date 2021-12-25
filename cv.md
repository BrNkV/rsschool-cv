# __Burenkov Igor__
## Contacts

- **Tel** — <a href="tel:+79811574035">+7 981 157 40 35</a>
- **Mail** — <a href="burenkov.igor@gmail.com">burenkov.igor@gmail.com</a>
- **Telegram** — <a href="https://t.me/burenkov">@burenkov</a>
- **City** — Saint-Petersburg
- [CodeWars](https://www.codewars.com/users/EveryBarry)
  
<img alt="CW" src="https://www.codewars.com/users/EveryBarry/badges/large">

---
## About me

I am 31 years old. An economist by profession. I have long wanted to learn how to develop useful services and applications. I study the frontend and backend. I really want to work in this area.

---
## Skills
Basic in:
* HTML
* CSS
* Git
* JavaScript
* ReactJS
* VueJS
* NodeJS
* Laravel

---
## Code Example

solving tasks of CodeWars  

Count the number of JavaScript developers coming from Europe

```js
function countDevelopers(list) {
  let count = 0;
 list.forEach(e => e.continent == "Europe" && e.language == "JavaScript" ?  count++ : count);
    return count;
}
```

Find the odd int
```js
function findOdd(arr) {
  let count = 0;
  for (let i = 0; i < arr.length; i++) {
    for (let j = 0; j < arr.length; j++) {
      if (arr[i] === arr[j]) count++;
    }
    if (count % 2 != 0) return arr[i];
  }
};
}
```
