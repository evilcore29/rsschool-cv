# Dzmitry Vladimirovich

## Contacts

[Linkedin](https://www.linkedin.com/in/%D0%B4%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9-%D0%B2-60b6001a1/) 

---

## Summary

I work for a company that develops software for efficient call centers. My goal for this course is to improve my core-js knowledge for more productive work.

---

## Skills

### Core

- HTML, CSS, JS
- React, Redux
- Git, VS Code, Postman, Ubuntu 20.04 (WSL)
- ANTD, Nivo, ApexCharts, Excel4NNode

### Touched

- PHP, SQL, MySQL
- nodejs, express, axios, npm, yarn, heroku, i18n

---

## Code Examples

[Solution for codewars kata](https://www.codewars.com/kata/5503013e34137eeeaa001648)

```
const diamond = ({ number }) => {
  if (number % 2 === 0 || number <= 0 || !number) return null;

  const levels = [];
  let counter = 1;

  while (counter <= number) {
    if (counter % 2 !== 0) levels.push(counter);
    counter++;
  }

  counter = 0;

  const asteriskArr = levels.map((item) => "*".repeat(item));

  const asteriskArrWithSpaces = asteriskArr.map(
    (item, index) => `${" ".repeat(levels.length - index - 1)}${item}\n`
  );

  const part1 = asteriskArrWithSpaces.join("");
  const part2 = asteriskArrWithSpaces
    .reverse()
    .filter((item, index) => index !== 0)
    .join("");

  return `${part1}${part2}`;
}
```

---

## Experience

- Database adminnistrator at "Экестросервис и Ко"
- Junior Frontend developer at [dealapp.io](https://dealapp.io)

---

## Education

I have specialized secondary education, and i’m self-studying in frontend.

### Courses

- IT-step (Minsk)
- Stepik:
  - Программирование начального уровня. JavaScript
  - Основы Git
  - JavaScript для начинающих
  - Jira: ведение задач на электронных досках
  - Веб-разработка для начинающих: HTML и CSS
  - Введение в базы данных
  - Hexlet: Введение в программирование (JavaScript ES6)
  - Введение в Linux
- Freecodecamp:
  - Responsive Web Design Certification
  - JavaScript Algorithms and Data Structures Certification

---

## Languages

English - Elementary
