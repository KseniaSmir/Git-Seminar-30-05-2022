# Инструкция по работе с git

## Что такое git

## Подготовка репозитория
Для того, чтобы создать репозиторий используется команда *git init*. Для этого необходимо написать в терминале в папке будущего репозитория *git init*.

## Создание "сохранений"

### Добавление файла к коммиту

Для добавления файла к коммиту используется команда *git add*. Пишется она следующим образом *git add <имя файла>* в терминале в папке с созданным репозиторием. 

### Создание коммита
Для создания нового "сохранения" используется команда *git commit*. Используестя она следующим образом: в терминале с папкой-репозиторием пишется *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**!!!

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в папке с репозитореем достаточно написать *git log*. 

## Перемещение между коммитами 
Для перемещениями между сохранениями используется команда *git checkout*.Для того, чтобы переместиться на указанный коммит в папке с репозиторием пишем *git checkout <номер коммита>*. **Номер коммита** берется из журнала изменений, о котором сказано выше. После перемещения на указанный коммит, мы попадаем в состояние *detached head*. Чтобы вернуться к обычной работе, необходимо написать *git checkout master*.

## Ветки в git
Для добавление новой ветки используется команда *git branch*. Ветки используются как черновики в них можно создавать и редактировать один документ в разных версиях. Если потребуется переключиться с одной ветки
на другую, вызовем команду *git checkout <имя ветки>*.

## Слияние веток и разрешение конфликтов

## Удаление веток