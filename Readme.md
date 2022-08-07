 # Инструкция по работе с GIT

## Что такое GIT?
    Одна из реализаций распределённых систем контроля версий, позволяющая организовать версионность, как локально, так и на удалённом сервере. Самая популярная платформа, реализующая  Git.
  * [GitHub](https://github.com)
 ## Подготовка репозитория
    Для создания в папке репозитория, необходимо открыть эту папку в терминале и написать команду "git init", после чего в этой папке создастся скрытая папка ".git" и таким образом папка станет репозиторием.
 ## Создание сохранений
 * ### Добавление файла к сохранению
        Для того чтобы добавить файл к сохранению, необходимо использовать команду "git add". В терминале с открытой папкой-репозиторием необходимо написать "git add <file name>", и этот файл добавится к сохранению.

 * ### Создания фиксаций  
        Для создания фиксации используется команда "git commit". Для этого в терминале с папко-репозиторием необходимо написать команду "git commit -m <сообщение к коммиту>. Сообщение писать **ОБЯЗАТЕЛЬНО**.

 * ### Просмотр состояния репозитория
        Для просмотра состояния репозитория используется команда "git status". В терминале с открытой папкой-репозиторием необходимо написать команду "git status" в результате можно увидеть следующие выводы:
        1. On branch *** nothing to commit - это означает, что не активных измененний
        2. Untracked file - это означает, что имеются файлы, не отслеживаемые системой контроля версий
        ...
 ## Перемещение между сохранениями
    Для перемещения между сохранениями используется команда "git checkout". Для этого в терминале папки-репозитории  необходимо написать "git checkout <номер сохранения>".
 ## Журнал изменений
    Для просмотра истории изменений используется команда "git log". Для этого в терминале с папкой-репозиторием необходимо написать "git log", и вы увидите список всех ваших коммитов в этой ветке с описанием Имени, Почты, Сообщением и Номером Коммита.

 ## Ветки в GIT

 ## Слияние веток и решение конфликтов

 ## Удаление веток
  