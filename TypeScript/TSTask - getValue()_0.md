tags: #TypeScript #generic #keyof #tsTask #астралСофт 
___

```TypeScript
const getValue = <T extends Record<string, unknown>>(obj: T, key: string): unknown => {
	obj(key)
}

getValue({name: 'Vasya'}, 'unknown');
```


___
### [[011 Решение задач JS, TS и React|Назад]]