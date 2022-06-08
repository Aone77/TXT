1. Создать внешний репозиторий c названием TXT -> new repositorie
2. Клонировать репозиторий TXT на локальный компьютер -> git clone https://github.com/Aone77/TXT.git
3. Внутри локального TXT создать файл “new.txt” -> touch new.txt
4. Добавить файл под гит -> git add new.txt
5. Закоммитить файл -> git commit -m "new.txt"
6. Отправить файл на внешний GitHub репозиторий -> git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT -> vim new.txt -> Esc -> :wq -> Enter
8. Отправить изменения на внешний репозиторий -> git commit -am "new.txt" 
9. Создать файл preferences.txt -> touch preferences.txt
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT -> vim preferences.txt  -> Esc -> :wq -> Enter
11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT -> vim skills.txt  -> Esc -> :wq -> Enter
12. Сделать коммит в одну строку -> git commit -m "new files"
13. Отправить сразу 2 файла на внешний репозиторий ->git add . &&  git commit -m "new files"
14. На веб интерфейсе создать файл bug_report.txt -> add file -> create bug_report
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> commit bug_report
16. На веб интерфейсе модифицировать файл bug_report.xml -> edit this file ->commit changes, добавить баг репорт в формате TXT -add file -> create new file "bug_report_2"
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе -> commit new file
18. Синхронизировать внешний и локальный репозиторий TXT -> git pull
