Привет, GitHub!!!
Hello, GitHub

# Инструкция для работы с Git

![Картинка](https://zalinux.ru/wp-content/uploads/2021/08/git.png)


* git init  - инициализация локального репозитория
* git status - получить информацию от git о его текущем состоянии
* git add - добавить файлы или папки к следующему коммиту 
* git add . - добавить все файлы и папки 
* git commit -m "коммит" - создание коммита
* git log - вывод на экран истории всех коммитов с их хеш-кодами
* git checkout - переход от одного коммита к другому коммиту 
* git checkout master - возращение к последней версии
* git diff - увидеть разницу между текущим файлом и закоммичеснным файлом

>[Тут](https://proglib.io/p/git-for-half-an-hour "Ссылка") Вы найдете полную инструкцию по работе с Git.

>[Тут](https://codepen.io/paulradzkov/pen/ZGoLgr "Ссылка") Вы найдете полную инструкцию по работе с Markdown.


# Инструкция

+ git branch - посмотреть список веток в репозитории
+ git branch new_branch_name - создаем новую ветку
+ git checkout branch_name - переход на конкретную ветку
+ git log --graph - вывод дерево веток
+ git merge branch_name - слияние (вызываем оттуда куда хотим добавить изменения)
+ git branch -m master Maстер - переиминовать на текущий момент ветку
+ git commit -a -m "___" = комманды git add . + commit -m
+ git branch -d branch_to_delete - удаление ветки