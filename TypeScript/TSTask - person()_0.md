tags: #TypeScript #tsTask #unknownINC 
____

```ts
type Optional <T extends {}, O extends keyof T> = any

type Person = {name: string, age:number; phone: number}
type OptionalAge = Optional<Person, 'age'> // {name:string, age?:number, phone:number}
type OptionalAgePhone = Optional<Person, 'age'| 'phone'> // {name:string; age?:number;phone?:number }
```

### Ответ

```ts

```

____
### [[011 Решение задач JS, TS и React|Назад]]