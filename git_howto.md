# Подсказки по git

Создание репозитория:
```sh
git init
```
Список незакоммиченных файлов:
```sh
git status
```
Изменения в ещё не добавленных в индекс файлов:
```sh
git diff
```
Список коммитов:
```sh
git log
```
Переключение между коммитами или ветками:
```sh
git checkou <имя ветки или номер коммита>
```
Добавить файл в индекс:
```sh
git add {file name}
```
Закоммитить добавленные в индекс файлы с сообщением:
```sh
git commit -m "message - сообщение "
``` 
Последний коммит в каждой из веток:
```sh
git branch -v
```
>Сообщение в коммите должно отображать изменения в файле 

Вывод каждого коммита в одну строку:
```sh
git log --oneline
```
![Пример отображения команды в терминале](https://www.malasngoding.com/wp-content/uploads/2024/02/git-log-oneline-1024x367.png)

## Ссылки 
[Ссылка на официальную инструкцию](https://git-scm.com/docs/user-manual "всплывающая подсказка")

Отоброжение всех веток:
```sh
git branch
```
Добавление новой ветки
```sh
git branch <name_new_dranch>
```
Удаление ветки:
```sh
git branch -d <name_branch>
```
Подсказки:
```sh
git <team_name> --help>
```
Разница между последними X коммитами:
```sh
git log -p-X
```
Вывести дерево веток:
```sh
git log --oneline --graph
```
Скачать изменения из удаленного репозитория и 
смержить:
```sh
git pull
```
Скачать изменения из удаленного репозитория и наложить незапущенные коммиты поверх скачанных:
```sh
git pull --rebase
```
Отправить локальный коммит в удаленный репозиторий:
```sh
git push
```


