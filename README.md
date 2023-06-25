# Telegram-магазин Botshop

Botshop - бот телеграм с web-app приложением для заказа кофе.

### Используемые технологии:

* Backend:
  + Python
  + База данных SQLite3
  + Библиотека Aiogram, используется FSM
* Frontend:
  + HTML
  + CSS
  + Javascript

## Описание работы бота

1. Регистрация пользователя при запуске бота.
2. Выбор списания или накопления баллов.
3. Открытие web-app приложения (сайта с каталогом товаров).
4. Пользователь выбирает сироп, размер кофе и добавляет в корзину.
5. Бот присылает счет для оплаты.
6. Если оплата производится, то присылается чек и данные отправляются в БД кофейни, а также в Excel-файл для исполнения заказа, у пользователя начисляются или списываются баллы.
7. Если оплата не производится в течение 5 минут, счет удаляется.


