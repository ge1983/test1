# Инструкция по работе с GIT

*Git* - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте. Чаще всего его используют для кода, но можно и для других файлов. Например, для картинок - полезно для дизайнеров.

С помощью Git-a можно откатить свой проект до более старой версии, сравнивать, анализировать или сливать свои изменения в репозиторий.

*Репозиторием* называют хранилище вашего кода и историю его изменений. Git работает локально и все ваши репозитории хранятся в определенных папках на жестком диске.

## git config --global user.name

Команда для установки имени пользователя 

## git config --global user.email

Команда для установки электронной почты

## git init

Команда *git init*  создает git репозаторий в текущей папке

## git add

Команда *git add* добавляет файл в список отслеживаемых (индексируемых) файлов

## git log 

Команда *git log* позволяет посмотреть историю изменений


## git status 

Команда *git status* показывает состояния репозитария

## git diff 

Команда *git diff* показывает изменения до commit

## Ветки в Git

*Ветка* - это набор commit (кружок), которые идут друг за другом

## git branch <название_ветки>

Команда *git branch <название_ветки>* или *git checkout -b <название_ветки>* создают новые ветки коммитов.

## git merge <название_ветки>

Команда *git merge <название_ветки>* соединяет две ветки. Для этого необходимо перейти в ту ветку куда нужно поместить данные из ветки.

## git branch -d <название_ветки>

Команда *git branch -d <название_ветки>* удаляет указанную ветку.
