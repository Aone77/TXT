1. Создать внешний репозиторий c названием XML -> new repositorie
2. Клонировать репозиторий XML на локальный компьютер -> git clone https://github.com/Aone77/XML.git
3. Внутри локального XML создать файл “new.xml” -> touch new.xml
4. Добавить файл под гит -> git add new.xml
5. Закоммитить файл -> git commit -m "new.xml"
6. Отправить файл на внешний GitHub репозиторий -> git push
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML -> vim new.xml  -> Esc -> :wq -> Enter
8. Отправить изменения на внешний репозиторий -> git commit -am "new files" -> git push
9. Создать файл preferences.xml -> touch preferences.xml
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML -> vim preferences.xml  -> Esc -> :wq -> Enter
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML -> vim skills.xml  -> Esc -> :wq -> Enter
12. Сделать коммит в одну строку -> git commit -m «new files"
13. Отправить сразу 2 файла на внешний репозиторий -> git add . && git commit -m "adding two files to the rep"
14. На веб интерфейсе создать файл bug_report.xml -> add file -> create bug_report
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> commit bug_report
16. На веб интерфейсе модифицировать файл bug_report.xml -> edit this file ->commit changes, добавить баг репорт в формате XML -add file -> create new file "bug_report_2"
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> commit new file
18. Синхронизировать внешний и локальный репозиторий XML -> git pull
