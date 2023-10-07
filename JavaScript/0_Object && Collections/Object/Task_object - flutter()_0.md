tags: #JavaScript #taskJS #object #unknownINC 
___

```js
//ЕСТЬ СТРУКТУРА ДАННЫХ

const structure = [
  "a.js",
  "b.js",
  {
    src: [
      "some.js",
      "other.js",
      {
        components: [
          "someComponent.js",
          {
            input: ["input.js"],
          },
        ],
      },
    ],
  },
];

/*
ФУНКЦИЯ ДОЛЖНА ВЕРНУТЬ 

[
  'a.js',
  'b.js',
  'src/some.js',
  'src/other.js',
  'src/components/someComponent.js'
]
*/

// РЕШЕНИЕ

const flutter = (arr, divider = "") => {
 // Ваш код здесь
};
```

### Ответ

```js
const flutter = (arr, divider = "") => {
  let res = [];

  arr.forEach((element) => {
    if (typeof element === "string") {
      res.push(divider + element);
    } else {
      let keyArr = Object.keys(element).join("");
      divider += keyArr + "/";

      res.push(...flutter(element[keyArr], divider));
    }
  });

  return res;
};
```



___
### [[011 Решение задач JS, TS и React|Назад]]