# Тестовый репозиторий
## Как я его создал:
1. Установил git с официального сайта: https://git-scm.com/install/windows
2. В Git bush создал папку `mkdir`
3. Инициализировал репозиторий - `git init`

## Как загрузил на github
1. Создал пустой репозиторий в гитхабе.
2. Команды в git bash
   ```
   $ git remote add origin https://github.com/semkafame/git-test.git
   $ git branch -M main
   $ git push -u origin main
   ```



## Полезные (основные) команды git
`git add <file>` - добавить файл к будущему коммиту

`git commit -m "комментарий"` - создать коммит с комментарием

`git status` - проверить текущий статус репозитория

`git log` - посмотреть историю коммитов. Есть опция `--oneline` для краткого вывода в одну строку

`git checkout <hash commit's>` - переключиться на любой коммит

`git checkout main` - вернуться к последней версии

`git pull` - скачать изменения с сервера

`git push` - загрузить изменения на cервер

`git clone` - клонировать репозиторий github, ссылку можно найти на странице репозитория в самом github под кнопкой "Code" (зеленая)