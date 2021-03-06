# Нотатки щодо курсових робіт 

Теми курсових робіт на 2020 рік знаходяться за [посиланням](https://github.com/pupenasan/ProgIngContrSystems/blob/master/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B8%D0%B9/%D0%B2%D1%80%D1%96%D0%B0%D0%BD%D1%82%D0%B8.md). Дозволяється  (навіть схвалюється) вибір власного варіанту.

Студентам треба розробити рішення (RPI+периферія+застосунок) для якогось застосування (варіанти для курсового). Одне рішення для команди з 3-4 осіб. Усі стадії ЖЦ проводити через загальнодоступний для проекту репозиторій в GitHub.

Структура системи повинна включати як мінімум наступні компоненти: 

* RPI як Edge засіб 
* датчики, якісь засоби індикації (можливо і виконавчі механізми)
* локальний візуальний ВЕБ-інтерфейс
* локальну базу-даних
* віддалену базу даних 
* веб-інтерфейс для віддаленого доступу 
* сервіси звітності 

Розробка програмної частини ведеться в NodeREd, дозволяється використовувати інші мови, або їх комбінацію без обмежень. 

## Технічні засоби, що передбачені в курсовій роботі.

- RPI3 (або RPI4): свій або зі своєю карткою
- фізичні датчики, підключені до RPI
- Arduino (за бажанням) 
- Node-RED як база для розробки ПЗ + dashboard
- MySQL (або за бажанням інша БД) як локальна БД
- Сервіси роботи з Telegram ботом, передбачається використання в якості діалогового інтерфейсу та повідомлень, тривог
- використання якогось сервісу по HTTP-Api в Інтернеті (за небхідності)
- сервіс [IFTTT](https://ifttt.com/)
- Git та GitHub: як основа для проектування, розробки ПЗ та документації, веб-сторінки
- VNC для локального та віддаленого доступу до RPI
- віртуалка для перевірки (за необхідності)
- хмарні сховища (пропонується Dropbox, Google складніше) 
- якийсь редактор MarkDown, наприклад [Typora](https://typora.io/) - для редагування документів
- якийсь редактор для рисування простих схем, наприклад Fritzing 
- [DIA](https://sourceforge.net/projects/dia-installer/) - редактор для створення схем   

## Зміст курсового проекту

1. Розробка вимог до системи та ПЗ.
   1. Загальний опис проектованої системи.
   2. Вимоги функцій та задач.
   3. Вимоги до видів забезпечення. 

2. Розробка архітектури та необхідної проектної документації.
   1. Технічна структура системи (структура комплексу технічних засобів).
   2. Принципові схеми та схеми підключення. 
   3. Відомість апаратних та програмних засобів.
   4. Програмна структура системи.
3. Методика перевірки та засобів тестування.
   1. Методика перевірки підсистеми Edge-рівня.
   2. Методика перевірки функцій архівування.
   3. Методика перевірки аналітичних сервісів.
   4. Методика перевірки діалогових сервісів. 
4. Розробка та налагодження програмного забезпечення та супровідної документації.
   1. ПЗ для Edge-рівня.
   2. Схеми інформаційної взаємодії 
   3. ПЗ для хмарних рішень
   4. WEB-інтерфейс

## Послідовність виконання проекту

Планується розробляти проект за методами Agile.

| Опис робіт                                                   | Терміни    | Примітки                          |
| ------------------------------------------------------------ | ---------- | --------------------------------- |
| Розробка першого варіанту технічних вимог: Формування першого варіанту вимог. Формування першого варіанту переліку необхідних засобів. | 2.03-22.03 | Вся команда.                      |
| Розробка методик перевірки ПЗ для Edge-рівня. Розробка та тестування першого варіанту ПЗ для Edge-рівня. Розробка локального Веб-інтерфейсу. Правки по вимогам. | 23.03-5.04 | Розділення   робіт за напрямками. |
| Розробка методик перевірки функцій архівування. Реалізація функцій збереження в локальній БД. Реалізація функцій збереження у віддаленій БД. Синхронізація локальної та віддаленої БД. Правки по вимогам. | 6.04-19.04 | Розділення   робіт за напрямками. |
| Розробка методик перевірки аналітичних сервісів. Реалізація функцій звітності. Реалізація функцій автоматизації з використанням хмарних сервісів.  Правки по вимогам. | 20.04-3.05 | Розділення   робіт за напрямками. |
| Методика перевірки діалогових сервісів. Розробка та перевірка чат-ботів. Розробка ВЕБ-сервісів для віддаленого контролю та керування.  Правки по вимогам. | 4.05-23.05 | Розділення   робіт за напрямками. |
| Доробка проекту. Доробка вимог. Розробка документації. Здача проекту. | 25.05-6.06 | Вся команда.                      |
|                                                              |            |                                   |
|                                                              |            |                                   |
|                                                              |            |                                   |

