tags: #JavaScript #taskJS #EventLoop #альфабанк #сбербанк 
___

```javascript
console.log('1') //

setTimeout(() => console.log('2'), 0) //

new Promise((resolve, reject) => {
	console.log('3') //
	reject()
})
	.then(() => console.log('4')) //
	.catch((console.log('5')) //
	.catch((console.log('2')) //
	.then((console.log('7')) //
	.then((console.log('8')) //
console.log('9') //
```

___
### [[011 Решение задач JS, TS и React|Назад]]