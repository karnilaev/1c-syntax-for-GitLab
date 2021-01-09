# 1c-syntax-for-GitLab

[![Gitter](https://badges.gitter.im/karnilaev/1c-syntax-for-GitLab.svg)](https://gitter.im/karnilaev/1c-syntax-for-GitLab?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Данная подсветка синтаксиса уже является частью подсветки в свежих версиях Gitlab. Устанавливать ее дополнительно уже не нужно.

В репозитории содержится бета-версия подсветки синтаксиса в GitLab.

Чтобы ее установить в старую версию gitlab нужно скопировать файл bsl.rb в папку с остальными правилами подсветки синтаксиса в GitLab. Посмотреть где находятся остальные лексеры можно с помощью команды:
```
sudo find / -name handlebars.rb
```
После перезапуска GitLab'а синтаксис 1С будет подсвечиваться.

![Пример подсветки](https://habrastorage.org/files/8b6/32e/66c/8b632e66c16a4563bbb156eff992069a.png)

