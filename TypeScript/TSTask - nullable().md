tags: #TypeScript #tsTask #nnullable #unknownINC 
____

```ts
const obj = {
	a: string,
	b: number
}

const nullableObj = {
	a: string | null,
	b: number | null
}
```

### Ответ

```ts
type Nullable<T> = {  
    [P in keyof T]: T[P] | null;
};
```

____
### [[011 Решение задач JS, TS и React|Назад]]