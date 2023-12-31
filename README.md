Ви отримали Технічне Завдання на розробку функціонального Telegram-бота з кореневою командою та налаштуваннями. Він матиме можливість обробляти повідомлення від користувачів та відповідати на них:

Мова Golang
Фреймворки github.com/spf13/cobra та gopkg.in/telebot.v3
Реалізувати обробники повідомлень для бота, які будуть відповідати на повідомлення в Telegram.
Створити функції-обробники повідомлень бота.
Додати ці функції до методів об'єкта telebot.Bot.
Обробляти повідомлення відповідно до їх типу та вмісту.
Це завдання дозволить вам:

Ознайомитися з основними поняттями та функціями мови Golang.
Ознайомитися з Telegram Bot API та вивчити як його використовувати для розробки телеграм бота.
Навчитися створювати та налаштовувати бота для взаємодії з користувачами в телеграмі.
Практикувати знання з програмування та збільшити свій досвід у розробці програмного забезпечення.
Зрозуміти потреби та вимоги розробників до інфраструктури.
Рекомендації до виконання:

Встановити Golang та налаштувати середовище розробки (Codespaces вже містить всі необхідні налаштування)
Створити новий проєкт на GitHub та налаштувати Git.
Додати залежність на бібліотеку github.com/spf13/cobra за домопогою import (практичне завдання продемонстровано в лекції 2.4)
Створити Telegram-бота за допомогою BotFather.
Отримати токен бота та зберегти його у змінну середовища TELE_TOKEN.
Імпортувати необхідні бібліотеки.
Встановити бібліотеку gopkg.in/telebot.v3 за допомогою go get.
Отримати токен бота зі змінної середовища.
Створити об'єкт бота за допомогою telebot.NewBot().
Додати обробник повідомлень за допомогою kbot.Handle(telebot.OnText, func(m telebot.Context)
Описати функцію-обробник, яка буде відповідати на повідомлення.
Зібрати, запустити та перевірити бота
Створити файл README з описом проєкту, посиланням на бота у форматі t.me/<Імʼя_бота>_bot, включаючи інструкції для встановлення та приклади використання команд.
Завантажити код на GitHub.
Надіслати посилання на репозиторій як відповідь
