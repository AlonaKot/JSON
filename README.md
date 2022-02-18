# JSON

1. Создать внешний репозиторий c названием JSON.
+ Открыть https://github.com/, залогиниться 
+ Зайти во вкладку `Repositories`
+ Нажеть `New`
+ Ввести название репозитория, сделать его общедоступным
+ Нажать `create repository`
2. Клонировать репозиторий JSON на локальный компьютер.
+ Открыть GitBash в папке, где будет храниться репозиторий
+ В командную стороку ввести команду `git clone + ссылка на репозиторий, который хотим клонировать`
3. Внутри локального JSON создать файл “new.json”.
+ `cd JSON` - перейти в локальный репозиторий
+ `touch new.json`
4. Добавить файл под гит.
+ `git add new.json` - для добавления определенного файла
+ `git add .` - для добавления всех файлов
 5. Закоммитить файл.
+ `git commit -m "new file"`
 6. Отправить файл на внешний GitHub репозиторий.
+ `git push`
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
+ `vim new.json`
+ нажать `i`
+ внести данные
```
{
	"full_name": "Alona Kot",
	"age": 25,
	"Pets": 1,
	"disired_Salary": "600$"
}
```
+ нажать `esc` ввести `:wq`
 8. Отправить изменения на внешний репозиторий. 
+ `git commit -am "edit file"; git push`
 9. Создать файл preferences.json
+ `cat > preferences.json`
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
+ Ввести текст 
```
 {
 "favorite_movie": "Indiana Jones",
 "favorite_serias": "Scrubs",
 "favorite_food": "Burgers",
 "country_you_would_like_to_visit": "Switzerland"
}
```
+ `ctrl + c` - выйти из редактирования
11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
+ `cat > skills.json`
+ ввести данные:
``` 
  {
	"skills": [
		"Basic theory",
		"Client-server architecture",
		"HTTP Server request methods",
		"HTTP Server responses codes",
		"Structures of requests and responses",
		"JSON, XML. Their structure",
		"API testing",
		"Removing and reading logs",
		"POSTMAN, FIDLER",
		"VPN",
		"Dev Tools for web browsers",
		"Mobile testing",
		"Feature iOS, Android, guidelines",
		"Building iOS Apps with Xcode",
		"Building Android Applications with Android Studio",
		"Interception of mobile traffic (sniffing) via CHARLES",
		"Proxy settings on iOS and Android",
		"Terminal Linux Ubuntu. Copying, creating, viewing, moving files on servers without a graphical interface",
		"Simple bash scripting, automation of routine tasks on the server",
		"Access to remote servers",
		"SQL fundamentals (Create, Delete, Drop, Insert Into, Select, From, Where, Join",
		"GIT",
		"JMETER",
		"Scrum Development Methodology",
		"Python. Creation of own client-server application." ]
  }
```
+ `ctrl + c` - выйти из редактирования
12. Отправить сразу 2 файла на внешний репозиторий.
+ `git add .; git commit -m "new files"; git push`
13. На веб интерфейсе создать файл bug_report.json.
+ В репозитории JSON нажать `add file`
+ Выбрать `Create new file`
+ Вести название файла
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ Нажать кнопку `Commit new file`
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
+ Открыть файл bug_report.json Выбрать редактирование. Ввести текст
``` 
{
"Summary": "Displaying a characteristic associated with a deleted group",
"Priority": "Major",
"Severity": "Midle",
"Status": "To do",
"Environment": "Desktop, Windows10 x64, Chrome97",
  "Descriprion": {
     "Precondition": [
         "Authorization in your personal account",
         "Switch the mode to store management (store_url/admin/home)",
         "In the sidebar, expand the 'Catalog' list",
         "The submenu 'Characteristics' is open",
         "Characteristics 'Test', 'Test 1', 'Test 2' are included in the group of characteristics 'Overall dimensions'",
         "The subgroup 'Groups of characteristics' is opened" ],
     "Steps to Reproduce": [
         "Click on the kebab menu next to the group 'Dimensions'",
         "Select the 'Delete' menu in the kebab" ],
     "Actual Result": [
        "Group deleted",
        "When switching to the 'Characteristics' tab, the characteristics 'Test', 'Test 1', 'Test 2' are displayed with binding to the deleted group" ],
     "Expected Result": [
        "Group deleted",
        "When switching to the 'Characteristics' tab, the characteristics 'Test', 'Test 1', 'Test 2' are displayed without binding to the remote group" ],
    },
  "Attachment": "https://drive.google.com/file/d/1KAg5XKZQIQC6zYaOxrDbs2ng1LBuOxcz/view?usp=sharing",
  "Assignee": null,
  "Reporter": "Alona Kot"
}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ Нажать кнопку `Commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON
+ `git pull`
 
 
