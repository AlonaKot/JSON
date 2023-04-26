# JSON

1. Create an external repository with a name JSON.
+ Open https://github.com/, Login in 
+ Go to tab _"Repositories"_
+ Press _"New"_
+ Enter the name of the repository, make it public
+ Press _"create repository"_
 2. Clone repository JSON to the local computer.
+ open GitBash in the folder where the repository will be stored
+ enter the command on the command line _git clone + link to the repository we want to clone_
 3. Create file inside local JSON _new.json_.
+ _cd JSON_ - go to local repository
+ _cat > new.json_
+ _ctrl + c_ - get out of editing
 4. Add file on git.
+ _git add new.json_ - to add a particular file
+ _git add ._ - to add all files
 5. Commit the file.
+ _git commit -m "new file"_
 6. Submit a file to an external GitHub repository.
+ _git push_
 7. Edit file content _new.json_ - write information about yourself (name, age, number of pets, future desired salary). Write everything in the format JSON.
+ _vim new.json_
+ press _"i"_
+ enter data
```
{
	"full_name": "Alona Kot",
	"age": 25,
	"Pets": 1,
	"disired_Salary": "600$"
}
```
+ press _"esc"_ enter _:wq_
 8. Push changes to an external repository. 
+ _git add new.json_ - add the changed file to git
+ _git commit -am "edit file"_ - commit changes
+ _git push_ - push modified file to external repository
 9. Create file _preferences.json_
+ _cat > preferences.json_
 10. To file _preferences.json_ add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in the format JSON.
+ Enter text 
 ```
{
 "favorite_movie": "Indiana Jones",
 "favorite_serias": "Scrubs",
 "favorite_food": "Burgers",
 "country_you_would_like_to_visit": "Switzerland"
}
```
+ _ctrl + c_ - get out of editing
 
 11. Create file _skills.json_ add information about the skills that will be studied on the course in the format JSON
 
 + _cat > skills.json_
 + Enter data:
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
+ _ctrl + c_ - get out of editing

 12. Upload 2 files at once to an external repository.
 + _git add ._
 + _git commit -m "new files"_
 + _git push_
 13. Create a file on the web interface _bug_report.json_.
 + In the repository JSON press _"add file"_
 + Choose _"Create new file"_
 + Enter the file name
 14. Do Commit changes (save) changes on the web interface.
 + Press the button _"Commit new file"_
 15. Modify the file on the web interface _bug_report.json_, add a bug report in the format JSON.
 + Open file _bug_report.json_ Select edit. Enter text
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
 16. Do Commit changes (save) changes on the web interface.
+ Press the button _"Commit changes"_.

 17.Synchronize external and local repository JSON
+ _git pull_
