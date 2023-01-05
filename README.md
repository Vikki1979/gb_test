# Руководство по установке Git
* скачать Git по ссылкам и установить.

 * скачать и установить VSC.

 * В VS Code запустить терминал (CTRL + `) и прописать *git --version* (должна появиться надпись типа *git version 2.39.0*. Версия Git может отличаться)
    
 * Нужно указать ваше имя и адрес электронной почты:
   
       git config --global user.enail "Ваш email"
       git config --global user.name "Ваше имя"
## Команды Git

* *git init* - инициализация репозитория Git
* *git add "somefile"* - добавить отдельный файл в область подготовленных данных
* *git add .* - добавить все файлы и папки в область подготовленных данных
* *git status* - просмотр статуса нужного репозитория
* *git commit -m "some changes"* - создание коммита в репозитории с сообщением об изменении
* *git log* - просмотр изменений, внесённых в репозиторий
* *git diff "somefile"* - просмотр не подготовленных для фиксации изменений
* *git checkout "имя контрольой точки"* - позволяет перемещаться между сохраненными точками
*git checkout "название ветки"* - возврат к актуальной версии в этой ветке

## Работа с GitHab

* *git clone* - Эта команда позволяет склонировать внешний репозиторий на наш ПК
* *git pull* - Эта команда позволяет скачать все из текущего репозитория и автоматически
* *git push* - Эта команда позволяет отправить нашу версию репозитория на внешний
репозиторий.
* *pull request* - Запрос разрешения владельца репозитория на внесение изменений в его репозиторий


