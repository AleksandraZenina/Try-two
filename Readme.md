# Инструкция по работе с Git и удаленными репозиториями

# Что такое Git?
**Git** это наиболее популярная реализация распределенной системы контроля версий. Самая популярная реализация **Git** - это [GitHab] (https://github.com/q)

## Подготовка репозитория
Для создания репозитория используется команда *git init*. Для этого необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминале с папкой написать команду *git init*.

## Создание коммита
Для создания коммита используется комада *git commit*. Для этого в терминале с папкой репозиторием необходимо написать *git commit -m  <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

### Добавление файла к коммиту
Для добавления файла к будущему коммиту используется команда *git add* Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*.

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого в терминале с папкой рпозиторием необходимл написать *git log*.

## Перемещение между коммитами
Для этого необходимо в журнале изменений как показано в предыдущей части найти необходимый коммит и его номер. После чего в терминале с папкой репозиторием написать команду git checkout <номер коммита>. После применения этой командыы вы попадете в состояние **
В котором никакие изменения сохраняться фиксироваться не будут. Для возврата в обчное состояние необходимо написать команду Git checkout master.

## Ветки в Git
### Создание веток в Git
Для создания новой ветки необходимо в папке-репозитории

## Удаление веток
