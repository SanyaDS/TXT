Homework 1 TXT

> Перед началом выполнения работы предварительно создаем папку например "GitHub" на локальном компьютере и в ней работаем через Terminal или GitBash.

1. Создать внешний репозиторий c названием TXT.  
`https://github.com/SanyaDS/TXT`
2. Клонировать репозиторий TXT на локальный компьютер.  
`$ git clone git@github.com:SanyaDS/TXT.git`
3. Внутри локального TXT создать файл new.txt.  
`$ cd txt`  
`$ touch new.txt`
4. Добавить файл под гит.  
`$ git status`  
`$ git add new.txt`
5. Закоммитить файл.  
`$ git commit -m "New file txt"`
6. Отправить файл на внешний GitHub репозиторий.  
`$ git push`
7. Отредактировать содержание файла new.txt - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
`$ vim new.txt`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
8. Отправить изменения на внешний репозиторий.  
`$ git status`  
`$ git add new.txt`  
`$ git commit -m "Update file txt"`  
`$ git push`
9. Создать файл preferences.txt.  
`$ touch preferences.txt`
10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.  
`$ vim preferences.txt`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.  
`$ touch skills.txt`  
`$ vim skills.txt`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
12. Сделать коммит в одну строку.  
`$ git status`  
`$ git add .`  
`$ git commit -m "New file txt"`
13. Отправить сразу 2 файла на внешний репозиторий.  
`$ git push`
14. На веб интерфейсе создать файл bug_report.txt.  
`# Создали файл bug_report.txt.`
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`# Сохранили файл bug_report.txt.`
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.  
`# Открыли файл bug_report.txt и модифицировали.`
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`# Сохранили файл bug_report.txt.`
18. Синхронизировать внешний и локальный репозиторий TXT.  
`$ git pull`
