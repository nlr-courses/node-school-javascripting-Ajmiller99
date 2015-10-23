Ви можете отримувати значення та маніпулювати властивостями об’єктів –– ключами та значеннями, які містить об’єкт –– схожим методом, як і у масивів.

Це приклад з **квадратними дужками**:

```js
var example = {
  pizza: 'yummy'
};

console.log(example['pizza']);
```

Код вище виведе рядок `'yummy'` до терміналу.

Окрім того, ви можете використати **крапковий запис (dot notation)**, щоб отримати ідентичний результат:

```js
example.pizza;

example['pizza'];
```

Обидва рядки коду повернуть `yummy`.

## Завдання:

Створити файл `object-properties.js`.

У цьому файлі оголосити змінну під назвою `food` ось так:

```js
var food = {
  types: 'only pizza'
};
```

Використайте `console.log()`, щоб вивести властивість `types` об’єкту `food` до терміналу.

Перевірте вашу відповідь запустивши команду:

```bash
javascripting verify object-properties.js
```