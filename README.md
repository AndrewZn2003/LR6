# LR6
### __Цель работы__:
Изучение базовых возможностей системы 
управления версиями, опыт работы с Git Api, опыт работы с локальным и 
удаленным репозиторием. 

### __Порядок выполнения работы__:
1. Создать аккаунт на сайте GitHub. 
2. Сделать копию в личное хранилище из 
https://github.com/Kurtyanik/LR6/ (Fork). 
3. Установить Git (https://git-scm.com/). 
4. После установки настроить клиент git, введя имя пользователя (Группа 
Фамилия И.О.) и email. 
5. Клонировать свой личный удалённый репозиторий на компьютер. 
6. Добавить файл через интерфейс GitHub. Подтянуть изменения в 
локальный репозиторий. 
Работу продолжать локально. 
7. Получить историю операций для каждой из веток. 
8. Просмотреть последние изменения. 
9. Выполнить слияние в ветку master, разрешив конфликт (можно 
использовать специальные редакторы или графический интерфейс git). 
10. Удалить побочную ветку после успешного слияния. 
11. Сделать изменения и зафиксировать их, оставляя комментарии, 
несколько раз. 
12. Сделать откат коммита. 
13. Создать ветку для отчёта. 
14. Начать оформлять отчёт в файле README.md (разрешены сторонние 
редакторы с подсветкой синтаксиса), используя markdown синтаксис 
(https://guides.github.com/features/mastering-markdown/): 
- В отчёте должен быть снимки экрана консоли и сторонних программ. 
Файлы снимков экрана разместить в отдельной папке. 
- Лог команд (без результатов их выполнения). 
При написании отчёта периодически делать коммиты, не забывать 
комментировать. 
15. Получить историю операций в форматированном виде (сокращённый 
хэш + дата + имя автора + комментарий). Добавить её в отчёт и сделать 
финальную фиксацию изменений. 
16. Отправить локальные изменения в сетевое хранилище GitHub (если 
делаете работу постепенно, то синхронизацию проводить в конце рабочего 
сеанса) 
В ЛК загрузить титульный лист и ссылку на свой репозиторий в формате PDF.

### __Ход работы__:
Клонирование удаленного репозитория на компьютер.
![Клонирование репозитория](Screens/Clone.png)
***
Добавление файла через интерфейс GitHub и подтяжка изменений в локальный репозиторий.
![Добавление изменений](Screens/Fetch.png)
***
Просмотр истории ветки branch1.
![История ветки branch1](Screens/LogBranchOne.png)
***
Просмотр истории ветки master.
![История ветки master](Screens/LogBranchMaster.png)
***
Выполнение слияния в ветку мастер.
![Слияние в ветку мастер](Screens/Merge.png)
***
Устранение возникшего при слиянии конфликта.
![Устранение конфликта](Screens/Conflict.png)
***
Выполнение коммита после разрешения конфликта.
![Коммит](Screens/CommitConflict.png)
***
Удаление ветки branch1.
![Удаление ветки](Screens/DeleteBranch.png)
***
Первое изменение.
![Первое изменение](Screens/ChangeOne.png)
***
Второе изменение.
![Второе изменение](Screens/ChangeTwo.png)
***
Просмотр истории ветки.
![История ветки](Screens/log.png)
***
Откат коммита.
![Откат коммита](Screens/RollbackCommit.png)
***
Создание ветки для отчета.
![Ветка отчета](Screens/Otchet.png)

### __Используемые в работе команды__:
- git clone - клонирование репозитория;
- git config --global user.<> - установка параметров на глобальном уровне;
- git fetch - получение изменений с удаленного репозитория на локальный;
- git log - просмотр истории веток;
- git status - просмотреть текущий статус репозитория;
- git merge - выполнение слияния;
- git branch -d "name" - удаление ветки;
- git checkout - переход на другую ветку или откат коммита;
- git branch - создание ветки;
- git push - отправка изменений с локального репозитория в глобальный.

### __Выводы__:
В ходе лабораторной работы я изучил базовые возможности системы 
управления версиями, получил опыт работы с Git Api, а также получил опыт работы с локальным и 
удаленным репозиторием. 