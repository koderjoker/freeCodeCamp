---
title: Functional Programming
localeTitle: Функциональное программирование
---
## Функциональное программирование

Функциональное программирование - это процесс создания программного обеспечения путем создания **чистых функций** , избежания **общего состояния** , **изменяемых данных** и **побочных эффектов** . Функциональное программирование является **декларативным** (говорит компьютеру, что вы хотите сделать), а не **обязательным** (говоря компьютеру точно, как это сделать), а состояние приложения протекает через чистые функции. Контрастируйте его с объектно-ориентированным программированием, где состояние приложения обычно используется совместно и совместно с методами в объектах.

### Почему функциональное программирование?

*   Это, как правило, более кратким
*   Это обычно более предсказуемо
*   Это легче проверить, чем объектно-ориентированный код

### Принятие на языках программирования

Многие языки программирования поддерживают функциональное программирование, такое как Haskell, F #, Common Lisp, Clojure, Erlang, OCaml. JavaScript также обладает свойствами нетипизированного функционального языка.

### Пользы

Функциональное программирование давно популярно в академических кругах, но с небольшим количеством промышленных приложений. Однако недавно в коммерческих или промышленных системах использовалось несколько известных языков функционального программирования. Например, язык программирования Erlang, разработанный шведской компанией Ericsson в конце 1980-х годов, используется для создания целого ряда приложений в таких компаниях, как T-Mobile, Nortel, Facebook, Électricité de France и WhatsApp.

### Функции более высокого порядка

Функции более высокого порядка - большая часть функционального программирования. Функция более высокого порядка - это функция, которая либо принимает функцию (s) в качестве параметра, либо возвращает функцию.

### карта

`map` - это функция более высокого порядка, которая вызывает функцию для каждого элемента списка и возвращает результаты в виде _нового_ списка.

Вот пример `map` :

```javascript
const myList = [6, 3, 5, 29]; 
 
 let squares = myList.map(num => num * num); // [36, 9, 25, 841] 
```

### Дополнительная информация:

*   [Википедия - Функциональное программирование](https://en.wikipedia.org/wiki/Functional_programming#Use_in_industry)
    
*   [KeyCDN - Функциональное программирование - что это такое и почему оно имеет значение?](https://www.keycdn.com/blog/functional-programming/)
    
*   [Средний - что такое функциональное программирование?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0)