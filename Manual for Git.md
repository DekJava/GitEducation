# Инструкция по работе с Git !
This is a [book "Pro Git"](https://gbcdn.mrgcdn.ru/uploads/asset/4245110/attachment/d4eb8c232f8f2bdf4e42ba7cb49e0c50.pdf)

## Список основных команд:

- ### git init 
>Инициализация локального репозитория. Это первая команда, 
которую нужно ввести в терминал перед работой над 
проэктом. Вызвать терминал можно командой Alt + F12


- ### git status

>с помощью этой команды можно **получить информацию** от 
git о его текущем состоянии файлов и проекта. Проверить
Были ли какие-то несохраненные изменения в проекте

### - git add  <file's name> 


> подготавливает  файлы к следующему коммиту


- ### git commit -m "massage"

>создание коммита. Данная команда сохраняет ваш проект
> в текущем состоянии. Таких сохранений может быть 
> сколь угодно и вы в любое время можете к нему вернуться,
> если что-то пошло не так


- ### git log

>вывод на экран истории всех коммитов с их хеш-кодами


- ### git checkout "name commit"
> переход от выбранному коммиту. Можно перейти, как 
по названию, так и по хэш-коду

- ### git checkout "name branch" 
> переход в другую ветку

- ### git diff
> показывает разницу между текущим и закоммиченным 
> файлом