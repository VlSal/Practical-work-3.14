## Первоначальная настройка Git

<span style="color:red">**git config --global user**</span> - задаёт имя пользователя и электронную почту, от которого будут идти коммиты. Вместо Vladimir Salamatin и vvvvvv@gmail.com (см. пример) нужно написать свои данные на латинице и указать вашу почту. Обратите внимание, она должна совпадать с той, на которую зарегистрирован аккаунт в Гитхабе.

<span style="color:red">**git config --list**</span> - Посмотреть настройки.

Пример транскрипции:

```bash=
git config --global user.name "Vladimir Salamatin"
git config --global user.email "vvvvvv@gmail.com"
```