# Personal Assistant
# Книга контактів dream_9_bot
​
Огляд
​
Книга контактів dream_9_bot - це простий додаток з інтерфейсом командного рядка (CLI), написаний на мові Python. Вона дозволяє користувачам керувати особистою адресною книгою, виконувати різні операції над контактами, позначати контакти специфічними тегами для зручного пошуку, сортувати файли у книзі контактів і навіть перевіряти погоду для вказаного міста.
​
Можливості
​
1. Додавання контактів: Легко додавайте нові контакти до вашої адресної книги з такими даними, як ім'я, країна, номери телефонів, дата народження, електронна пошта та нотатки.
2. Пошук контактів: Виконуйте пошук за різними категоріями, такими як ім'я, країна, телефони, день народження, електронна пошта або нотатки.
3. Редагування контактів: Зміна існуючої контактної інформації, включаючи ім'я, країну, телефони, день народження, електронну пошту або нотатки.
4. Видалити контакти: Видалення контактів, вказавши ім'я або номер телефону.
5. Зберегти та завантажити: збереження адресної книги у файл або завантаження її з файлу для зручного зберігання даних.
6. Перегляд контактів: Відображення всіх контактів у табличному форматі, що полегшує перегляд і керування адресною книгою.
7. Інформація про погоду: Перевірте поточну погоду для вказаного міста за допомогою OpenWeatherMap API.
8. Привітання контактів: Перевіряйте кого з контактів необхідно буде привітати в поточному тижні.
​
Використання
​
1. Встановлення: Переконайтеся, що у вас встановлено Python, і встановіть необхідні залежності за допомогою:
   pip install rich, pip install requests та pip install setuptools
2. Запустіть програму: Запустіть скрипт, виконавши наступну команду: python __main__.py
3. Команди: Використовуйте наступні команди в dream_9_bot:
     'add': Додати новий контакт.
     'search': Пошук контактів за вказаними критеріями.
     'edit': редагування наявної контактної інформації.
     'remove': Видалити контакт.
     'save': Зберегти адресну книгу у файл.
     'load': Завантажити адресну книгу з файлу.
     'congratulate': Перевірити у кого з контактів скоро день народження.
     'view': Переглянути всі контакти в табличному форматі.
     'weather': Отримати погоду для вказаного міста.
4. Вихід: Щоб вийти з програми, скористайтеся командою exit.
​
Функція погоди
​
Огляд
​
Книга контактів dream_9_bot містить функцію погоди, яка дозволяє перевірити погоду для певного міста. Скористайтеся командою weather, за якою слідує назва міста, або вам буде запропоновано ввести назву міста під час виконання команди.
​
Примітка: Переконайтеся, що у вас є дійсний ключ API для функції погоди. Замініть у скрипті заповнювач api_key на ваш дійсний ключ API: api_key = 'your_openweathermap_api_key'
​
Залежності
​
Rich: Бібліотека Python для розширеного тексту і красивого форматування в терміналі.
​
Функція тегів
​
Огляд
​
Функція тегів у книзі контактів dream_9_bot дозволяє користувачам позначати свої контакти специфічними тегами для подальшого зручного пошуку та організації. Теги є корисним інструментом для класифікації контактів за різними критеріями.
​
Використання тегів
​
1. Додавання тегів до контактів:
 Використайте команду 'tag' для додавання тегів до свої контактів.
 Під чам виконання команди, система запитає вас iм'я контакту, якому ви хочете додати теги.
 Потім введіть теги, розділені пробілами, які ви хочете призначити цьому контакту.
     Приклад використання:
         Команда: tag_search
         Введіть ім'я контакту: Ольга
         Введіть теги(наприклад, friends family): friiends family
​
2. Пошук за тегами
 Використайте команду 'tag_search' для пошуку контактів за конкретним тегом.
 Введіть тег, і програма виведе список контактів, які мають цей тег.
     Приклад використання:
         Команда: tad_search
         Введіть тег для пошуку(накприклад, family): family
​
3. Видалення тегів:
 Використайте команду 'remove_tag' для видалення тегів з контакту.
 Введіть ім'я контакту, а потім введіть теги, які ви хочете видалити.
     Приклад використання:
         Команда: remove_tag
         Введіть ім'я контакту: Ольга
         Введіть теги для видалення(наприклад, family): family
​
Залежності
​
Для користуванням всіма функцціями dream_9_bot, переконайтеся що у вас встановлено бібліотеку Rich, виконавши наступну команду:
pip install rich

Функція сортування файлів

Огляд

Функція сортування файлів  призначена для сортування різних типів файлів у папки згідно їхнього формату в межах каталогу, вказаного користувачем. Нижче наведено опис розподілу файлів за їхнім форматом:

Зображення
 JPEG: Файли у форматі JPEG сортуються у папку images/JPEG.
 PNG: Файли у форматі PNG сортуються у папку images/PNG.
 JPG: Файли у форматі JPG сортуються у папку images/JPG.
 SVG: Файли у форматі SVG сортуються у папку images/SVG.
​
Відео
 AVI: Відеофайли у форматі AVI сортуються у папку video/AVI.
 MP4: Відеофайли у форматі MP4 сортуються у папку video/MP4.
 MOV: Відеофайли у форматі MOV сортуються у папку video/MOV.
 MKV: Відеофайли у форматі MKV сортуються у папку video/MKV.
​
Документи
 DOC: Документи у форматі DOC сортуються у папку documents/DOC.
 DOCX: Документи у форматі DOCX сортуються у папку documents/DOCX.
 TXT: Текстові документи сортуються у папку documents/TXT.
 PDF: Файли у форматі PDF сортуються у папку documents/PDF.
 XLSX: Електронні таблиці у форматі XLSX сортуються у папку documents/XLSX.
 PPTX: Презентації у форматі PPTX сортуються у папку documents/PPTX.

Аудіо
 MP3: Аудіофайли у форматі MP3 сортуються у папку audio/MP3.
 OGG: Аудіофайли у форматі OGG сортуються у папку audio/OGG.
 WAV: Аудіофайли у форматі WAV сортуються у папку audio/WAV.
 AMR: Аудіофайли у форматі AMR сортуються у папку audio/AMR.
​
Інші
 Файли, які не відповідають жодному зазначеному формату, сортуються у папку OTHER.

Архіви
 Архівні файли сортуються у папку archives/ARCHIVES.

Після сортування порожні папки видаляються для підтримки чистоти та організації в каталозі. Якщо виникають проблеми з видаленням папок, виводиться відповідне повідомлення про помилку.

Зазначте шлях до каталогу, щоб використовувати цю функцію та організувати ваші файли за зазначеними критеріями.

Для використання цієї функції переконайтеся, що у вас встановлено необхідні бібліотеки та виконали встановлення за допомогою:
pip install rich

## Наша команда:
* Developer: [chAek](https://github.com/aektann89)
* Developer: [Andrew](https://github.com/Andrewchv)
* Developer: [Aryna Reutska](https://github.com/xrendezvous)
* Scrum Master + Developer: [Olha](https://github.com/HelgaTsar)
* Team Lead + Repository Owner + Developer: [Serg](https://github.com/CodeCraftSerg) (ex [Obi-Wan-Serg](https://github.com/Obi-Wan-Serg))