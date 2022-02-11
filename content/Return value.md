---
term: Return value
translations:
  - повернене значення
referenceTranslations:
  - source: "Microsoft Language Portal"
    text: "Повернуте значення"
  - source: "Microsoft Language Portal"
    text: "Вернуте значення"
  - source: "Microsoft Language Portal"
    text: "Код повернення"
  - source: "Microsoft Language Portal"
    text: "Повертане значення"
  - source: "Microsoft Language Portal"
    text: "Отримане значення"
  - source: "Microsoft Language Portal"
    text: "Вихідне значення"
  - source: "Англійсько-український словник сучасних термінів з ІТ (2011-2011)"
    text: "Значення повернення"
---

**Повернене значення** – те значення, яке функція віддає, коли завершується. Наприклад:

```js
function add(...items) {
  return items.reduce((accumulator, item) => accumulator + item, 0);
}
const result = add(1, 2, 3);
console.log(result);
// 6
```

У прикладі вище 6 – повернене значення.

Якщо функція не повертає значення явно – поверненим значенням є `undefined`.

Функція з модифікатором `async` завжди повертає об‘єкт типу `Promise`.