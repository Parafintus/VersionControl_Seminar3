# VersionControl_Seminar3
Репозиторий для пулл-реквестов по Введению в контроль версий в Geekbrains

## Начальная работа с системой контроля версий

* `git version` - комманда для проверки версии git

* `git init` - инициальизируем пустой репозиторий
* `git status` - проверяем текущее состояние файла

* `git add имя_файла_с_расширением` - добавляем версионность файлу
 
* `git add .` - добавляем версионность всем файлам в папке

* `git commit -m "Сообщение"` - комманда для фиксации изменений файлов

* `git commit -am "Сообщение"` - фиксация изменений. не требует `git add`

* `git diff` - вывод изменений на текущий момент по отношению к последнему коммиту

* `git log` - вывод истории коммитов в хронологическом порядке

* `git checkout "хэш коммита"` - переход между изменениями

* `git checkout master` - возврат к текущему состоянию

* `git clone <ссылка на репозиторий> <название папки> `- клонирование репозитория в указанную папку

## Что такое Git?

Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля в мире. 

## Подготовка репозитория

Для создания репозтория необходимо выполнить команду *`git init`* в папке с репозиторием

## Git add

Для добавления изменений в коммит используется команда *`git add`*. Чтобы использовать команду *`git add`*, напишите *`git add имя_файла`* или *`git add .`*

## Создание коммитов

Для того, чтобы создать коммит (сохранение), необходимо выполнить команду *`git commit -m "Сообщение"`* или *`git commit -am "Сообщение"`*

## Создание ветки

Для того, чтобы создать ветку, нужно использовать *`git branch имя_ветки`* или *`git checkout -b имя_ветки`* (последняя команда ещё и переместит в новую ветку)

## Git log
Чтобы посмотреть историю комитов, нажмите *`git log`*. Если нужно кратко, то *`git log --oneline`*. Для отображения веток команда *`git log --graph`*. 

## Слияние веток
Чтобы слить ветку в текущую, нажмите *`git merge имя_ветки`*








*`git clone ссылка`* - команда для загрузки удаленного репозитория

*`git push`* - команда для отправки из локального репозитория в удаленный

*`git pull`* - команда для подгрузки изменений из удаленного репозитория в локальный

*`git branch`* - посмотреть список веток

*`git branch new_branch`* - создать новую ветку

*`git branch -d имя_ветки`* - удалить ветку

*`git checkout -b название ветки`* - переход к другой ветке и, если ее нет, то создать