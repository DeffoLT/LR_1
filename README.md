# LR_1

1. Що таке Git?
   Git – це програмне забезпечення для контролю версій.

2. В якому статусі можуть перебувати файли при роботі з Git?
   Збережений - дані безпечно збережено в локальній базі даних
   Змінений - файл внесено редагування, які ще не збережено в базі даних
   Індексований стан виникає тоді, коли ви позначаєте змінений
   файл у поточній версії, щоб ці зміни ввійшли до наступного знімку
   коміту.

3. Для чого використовується команда add?
   git add ім’я_файлу
   Додає необхідний файл до репозиторію.

4. Для чого використовується команда status?
   git status
   Перевіряє чи додані файли до репозиторію.

5. Для чого використовується команда commit?
   git commit -m "Назва коміту"
   Коміт – фіксація стану сховища в певний момент часу, тобто фіксація змін.

6. Для чого використовується команда init?
   git init
   Ініціалізація Git у папці проекту.

7. Що необхідно писати в коментарях комітів?
   Написання коментаріїв
   Інформацію що було змінено, де змінено, чому змінено.

8. Як переглянути список комітів?
   git log --reflog

9. Для чого використовується команда checkout?
   git checkout
   Для того, щоб переключатися між гілками або відновити файли робочого дерева.
   При перемиканні гілки відбувається оновлення файлів в робочому каталозі відповідно до версії, 
   що зберігається в цій гілці, а Git починає записувати все нові комміти в цій гілці
