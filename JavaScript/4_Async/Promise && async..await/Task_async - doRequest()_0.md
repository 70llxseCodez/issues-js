tags: #JavaScript #taskJS #promise #itOne 
____

```js
// реализовать функцию, которая делать сетевой запрос, если запрос завершается ошибкой - повторяет попытку через секунду.
// И так три раза. 
// После трех неудачных попыток - завершается ошибкой. Или возвращает успешный результат.

 function runWithRetry (url, times = 3) {
	 // Ваш код здесь
 }
 
function doRequest() { 
	fetch(url) 
		.then((data) => res(data.json())) 
		.catch((e)=>{ count-- 
			if(count !==0){ 
				settimeout(doRequest,1000) 
			}) 
		rej() })) 
	} 
})  
  
doRequest()
```

```js
getData('[https://api.openweathermap.org/data/2.5/weather?q=moscow(https://api.openweathermap.org/data/2.5/weather?q=moscow "https://api.openweathermap.org/data/2.5/weather?q=moscow")', 3) 
	.then((response) => { console.log(response) }) 
	.catch((err) => { console.log('Error', err.message) })
```

### Ответ

```js

```

___
### [[011 Решение задач JS, TS и React|Назад]]