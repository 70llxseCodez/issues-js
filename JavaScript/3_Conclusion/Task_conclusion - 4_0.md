tags: #JavaScript #taskJS #conclusion #астон
___

```js
var l = 25;
var x = 11;

function bar(foo) {
	var x = 30;
	foo()
}

function foo() {
	console.log('x', x) //
}

foo.x = 20;
bar.x = 40;

bar(foo);

l.x = 100;

console.log('foo.x', foo.x) //
console.log(bar.l) //
console.log(l.x) //
```

### Ответ

```js

```


___
### [[011 Решение задач JS, TS и React|Назад]]