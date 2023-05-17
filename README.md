# TXT

###  1. Создать внешний репозиторий c названием TXT

    Repositories -> New -> Repos Name:TXT -> Check "Add a README file" -> Press "Create repository"
   
###  2. Клонировать репозиторий TXT на локальный компьютер

    git clone <repository HTTPS>
    
###  3. Внутри локального TXT создать файл "new.json"

    touch new.txt
    
### 4. Добавить файл под гит

    git add . или git add new.txt
    
### 5. Закоммитить файл

    it commit -m "любой комментарий"
    
### 6. Отправить файл на внешний GitHub репозиторий

    git push
    
### 7. Отредактировать содержание файла “new.txt” написать информацию о себе в формате TXT (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)

    vim new.txt -> input data -> esc -> enter ":wq"
    
### 8. Отправить изменения на внешний репозиторий

    git add . && git commit -m "любой комментарий"
    git push
    
### 9. Создать файл preferences.txt

    touch preferences.txt
    
### 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT

    vim preferences.txt -> insert data -> esc -> enter ":wq"
    
### 11. Создать файл skills.txt. Добавить информацию о скиллах которые будут изучены на курсе в формате TXT

    touch skills.txt
    
### 12. Отправить сразу 2 файла на внешний репозиторий

    git commit -a -m "любой комментарий"  
    git push
    
### 13. На веб интерфейсе создать файл bug_report.txt

    Add file -> Create new file -> Name: bug_report.txt
    
### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе

    Commit New File
    
### 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT

    Choose bug_report.txt -> Edit this file
    
### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе

    Commit changes
    
### 17. Синхронизировать внешний и локальный репозиторий TXT

    git pull
   
