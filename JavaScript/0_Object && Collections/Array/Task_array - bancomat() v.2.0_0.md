tags: #JavaScript #taskJS #object #array #райфайзенбанк 
____

```js
const atm = (currency, count) => {
// we have values:
// - "EUR": 5, 10, 20, 50, 100, 200, 500,
// - "USD": 1, 2, 5, 20, 50, 100,
// - "RUB": 50, 100, 500, 1000, 5000
// your code here...
};

 console.log(atm("XSF", 1000)); // 'Sorry, have no XSF.'
 console.log(atm("rub", 12341)); // 'Can not do 12341 RUB. Value must be divisible by 10!'
 console.log(atm("USD", 842)); // '8 * 100 USD, 2 * 20 USD, 1 * 2 USD'
 console.log(atm("euR", 1000)); // '2 * 500 EUR'
```

### Ответ

```js

```

___
### [[011 Решение задач JS, TS и React|Назад]]