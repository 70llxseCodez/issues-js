tags: #JavaScript #taskJS #polyfill #some #альфабанк 
____

```js
// Условие: написать полифил для метода some
// [2, 5, 8, 1, 4].some((element) => element > 10); ---> false
// [12, 5, 8, 1, 4].some((element) => element > 10); ---> true

Array.prototype.mySome = function(cb) {
	// Ваш код здесь
}
```

### Ответ

```javascript
// Условие: написать полифил для метода some
// [2, 5, 8, 1, 4].some((element) => element > 10); ---> false
// [12, 5, 8, 1, 4].some((element) => element > 10); ---> true

Array.prototype.mySome = function(cb) {
	for (let i = 0; i < this.length; i++) {
		if(cb(this[i], i, this)){
		return true
		}
	}
	return false
} 
```


___
### [[011 Решение задач JS, TS и React|Назад]]