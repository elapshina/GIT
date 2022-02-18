# JSON
 1. Создать внешний репозиторий c названием JSON
 - зайти на https://github.com
 - войти в свой аккаунт
 - нажать кнопку `New repository`
 - на открывшейся странице ввести имя репозитория (Repository name)
 - нажать кнопку `Create repository`

2. Клонировать репозиторий JSON на локальный компьютер
 - нажать кнопку `Code`
 - скопировать ссылку на репозиторий
 - в терминале зайти в папку в которой будет локальный репозиторий
 - `git clone https://github.com/elapshina/JSON.git`
 
3. Внутри локального JSON создать файл “new.json”
-  `cd JSON`
-  `touch new.json`

 4. Добавить файл под гит
 - `git add new.json`
 
 5. Закоммитить файл
 - `git commit -m "add new.json`

6. Отправить файл на внешний GitHub репозиторий
- `git push`

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
 - `nano new.json`

 ```
 {
        "full_name":"Ekaterina Lapshina",
        "age":32,
        "number_of_pets":0,
        "future_desired_salary":"1000$"
 }
 ```

8. Отправить изменения на внешний репозиторий
- `git add new.json`
- `git commit -m "modified new.json"`
- `git push`

9. Создать файл preferences.json
-  `nano preferences.json`


10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
```
{
	"favorite_movie":"World War Z",
	"favorite_series":"Squid Game",
	"favorite_food":"Pasta",
	"favorite_season":"Summer",
	"country_you_would_like_to_visit":"Portugal"
}
```

11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
- `nano sklls.json`
```
{
"skills":[
	"Basic theory",
	"Client-server architecture",
	"HTTP Methods of requests to the server",
	"HTTP server response codes",
	"Structures of HTTP requests and responses",
	"What is JSON, XML. Their structure",
	"API testing via Postman",
	"Removing and reading logs from an external 
    server",   
	"Sniffing http web traffic via Charles and 
    Fiddler",
	"Dev Tools of web browsers",
	"VPN.ow it works, why you need it, how to use
    it, tool options",
	"Mobile testing",
	"Feature of iOS, Android, guidelines",
	"Building iOS applications on XCode",
	"Building Android applications on Android
    Studio",
	"ADB (android device management)",
	"Setting up proxy and vpn on iOS and Android",
	"Interception of mobile traffic via Charles and
    Fiddler on iOS and Android",
	"Command line terminal Linux",
	"Basics of bash scripting, automation of
    routine tasks on the server",
	"Access to remote servers",
	"SQL basics",
	"Postgres database",
	"Non-relational database Redis",
	"Load testing in Jmeter",
	"Scrum development methodology",
	"Python. Learning the basics. Creating a
    client-server application"
	]
}
```

 12. Отправить сразу 2 файла на внешний репозиторий
 - `git add .`
 - `git commit -m "add preferences.json and skills.json"`
- `git push`

13. На веб интерфейсе создать файл bug_report.json
- Войти в репозиторий JSON
- Нажать кнопку `Add file`
- Выбрать `Create new file`
- В поле Name your file ввести bug_report.json

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 - Нажать кнопку `Commit changes`

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
 - открыть файл bug_report.json
 - перейти в режим редактирования
```
{
    "Project":"Ewa",
    "Summary":"Start page: The button to enter email is not clickable",
    "Descriprion":"{
    	"STR":{"1":"Run app",
            "2":"Click button to enter email"},
    	"Actual result":"The button to enter email is not clickable",
    	"Expected result":"The button to enter email is clickable and an input field should appear"
					},
     "Environment":"Android 12", 
     "Attachment":"fghfmsk.mp4",
     "Lables": "email",
     "Severity":"major",
     "Priority":"medium"
}
```

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- Нажать кнопку `Commit changes`

17. Синхронизировать внешний и локальный репозиторий JSON
-  `git pull`

# XML

1. Создать внешний репозиторий c названием XML
- зайти на https://github.com
 - войти в свой аккаунт
 - нажать кнопку `New repository`
 - на открывшейся странице ввести имя репозитория (Repository name)
 - нажать кнопку `Create repository`

 2. Клонировать репозиторий XML на локальный компьютер
 - нажать кнопку `Code`
 - скопировать ссылку на репозиторий
 - в терминале зайти в папку в которой будет локальный репозиторий
 - `git clone https://github.com/elapshina/XML.git`

3. Внутри локального XML создать файл “new.xml”
-  `cd XML`
-  `touch new.xml`

 4. Добавить файл под гит
 -  `git add new.xml`

 5. Закоммитить файл
 - `git commit -m "add new.xml"`
 
6.Отправить файл на внешний GitHub репозиторий
- `git push`

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML
 - `vim new.xml`
 ```
 <information_about_me>
 	<fullName>Ekaterina Lapshina</fullName>
	<age>32</age>
	<number_of_pets>0</number_of_pets>
	<future_desired_salary>1000$<future_desired_salary>
</information_about_me>
```
8. Отправить изменения на внешний репозиторий
- `git add new.xml`
- `git commit -m "modified new.xml"`
- `git push`

 9. Создать файл preferences.xml
  `vim preferences.xml`

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
```
<My_preferences>
	<favorite_movie>World War Z</favorite_movie>
	<favorite_series>Squid Game</favorite_series>
	<favorite_food>Pasta</favorite_food>
	<favorite_season>Summer</favorite_season>
	<country_you_would_like_to_visit>Portugal</country_you_would_like_to_visit>
</My_preferences>
```


 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 - `vim skills.xml`
 ```
 <My_skills>
    <one>Basic theory</one>
	<two>Client-server architecture</two>
	<three>HTTP Methods of requests to the server</three>
	<four>HTTP server response codes</four>
	<five>Structures of HTTP requests and responses</five>
	<six>What is JSON, XML. Their structure</six>
	<seven>API testing via Postman</seven>
	<eight>Removing and reading logs from an external 
    server</eight>   
	<nine>Sniffing http web traffic via Charles and 
    Fiddler</nine>
	<ten>Dev Tools of web browsers</ten>
	<eleven>VPN.ow it works, why you need it, how to use
    it, tool options</eleven>
	<twelve>Mobile testing</twelve>
	<thirteen>Feature of iOS, Android, guidelines</thirteen>
	<fourteen>Building iOS applications on XCode</fourteen>
	<fifteen>Building Android applications on Android
    Studio</fifteen>
	<sixteen>ADB (android device management)</sixteen>
	<seventeen>Setting up proxy and vpn on iOS and Android</seventeen>
	<eighteen>Interception of mobile traffic via Charles and
    Fiddler on iOS and Android</eighteen>
	<nineteen>Command line terminal Linux</nineteen>
	<twenty>Basics of bash scripting, automation of
    routine tasks on the server</twenty>
	<twentyOne>Access to remote servers</twentyOne>
	<twentyTwo>SQL basics</twentyTwo>
	<twentyThree>Postgres database</twentyThree>
	<twentyFour>Non-relational database Redis</twentyFour>
	<twentyFive>Load testing in Jmeter</twentyFive>
	<twentySix>Scrum development methodology</twentySix>
	<twentySeven>Python. Learning the basics. Creating a
    client-server application</twentySeven>

</My_skills>
```

 12. Сделать коммит в одну строку

 - `git add . | git commit -m" add preferences.xml skills.xml`
 13. Отправить сразу 2 файла на внешний репозиторий
  - `git push`

 14. На веб интерфейсе создать файл bug_report.xml
 - Войти в репозиторий XML
- Нажать кнопку `Add file`
- Выбрать `Create new file`
- В поле Name your file ввести bug_report.xml

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 - Нажать кнопку `Commit changes`

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
- открыть файл bug_report.xml
 - перейти в режим редактирования
```
<bugReport>
    <Project>Ewa</Project>
    <Summary>Start page: The button to enter
	  email is not clickable</Summary>
    <Descriprion>
      <STR>
        <one>Run app</one>
        <two>Click button to enter email</two>
      </STR>
      <Actual_result>The button to enter email is
	    not clickable</Actual_result>
      <Expected_result>The button to enter email
	    is clickable and an input field should
	    appear</Expected_result>
    </Descriprion>
    <Environment>Android 12</Environment> 
    <Attachment>fghfmsk.mp4</Attachment>
    <Lables>email</Lables>
    <Severity>major</Severity>
    <Priority>medium</Priority>
</bugReport>
  ```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 - Нажать кнопку `Commit changes`

18. Синхронизировать внешний и локальный репозиторий XML
- `git pull`

# TXT
 1. Создать внешний репозиторий c названием TXT
 - зайти на https://github.com
 - войти в свой аккаунт
 - нажать кнопку `New repository`
 - на открывшейся странице ввести имя репозитория (Repository name)
 - нажать кнопку `Create repository`

 2. Клонировать репозиторий TXT на локальный компьютер
 - нажать кнопку `Code`
 - скопировать ссылку на репозиторий
 - в терминале зайти в папку в которой будет локальный репозиторий
 - `git clone https://github.com/elapshina/TXT.git`

 3. Внутри локального TXT создать файл “new.txt”
 Внутри локального JSON создать файл “new.json”
-  `cd TXT`
-  `touch new.txt`

 4. Добавить файл под гит
 `git add new.txt`

 5. Закоммитить файл
 - `git commit -m "add new.txt`

 6. Отправить файл на внешний GitHub репозиторий
 - `git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT
 - `nano new.txt`

 ```
 full name:Ekaterina Lapshina
age:32
number of pets:0
future desired salary:1000$
```

 8. Отправить изменения на внешний репозиторий
 - `git add new.txt`
 - `git commit -m "modified new.txt"`
 - `git push`
 9. Создать файл preferences.txt
 - `nano preferences.txt`
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT

 ```
favorite movie: World War Z
favorite series: Squid Game
favorite food: Pasta
favorite season: Summer
country you would like to visit: Portugal
```

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
- `nano skills.xml`
```
skills:

Basic theory
Client-server architecture
HTTP Methods of requests to the server
HTTP server response codes
Structures of HTTP requests and responses
What is JSON, XML. Their structure
API testing via Postman
Removing and reading logs from an external server  
Sniffing http web traffic via Charles and Fiddler
Dev Tools of web browsers
VPN.ow it works, why you need it, how to use it, tool options
Mobile testing
Feature of iOS, Android, guidelines
Building iOS applications on XCode
Building Android applications on Android Studio
ADB (android device management)
Setting up proxy and vpn on iOS and Android
Interception of mobile traffic via Charles and
Fiddler on iOS and Android
Command line terminal Linux
Basics of bash scripting, automation of routine tasks on the server
Access to remote servers
SQL basics
Postgres database
Non-relational database Redis
Load testing in Jmeter
Scrum development methodology
Python. Learning the basics. Creating a client-server application
```

 12. Сделать коммит в одну строку

 - `git add . | git commit -m" add preferences.txt skills.txt`
 13. Отправить сразу 2 файла на внешний репозиторий
  - `git push`
 14. На веб интерфейсе создать файл bug_report.txt
- Войти в репозиторий TXT
- Нажать кнопку `Add file`
- Выбрать `Create new file`
- В поле Name your file ввести bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 - Нажать кнопку `Commit changes`
 
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT
 - открыть файл bug_report.txt
 - перейти в режим редактирования
 ```
 Project:Ewa
Summary:Start page:The button to enter email is not clickable
Descriprion:
- STR:
1. Run app
2. Click button to enter email
- Actual result:The button to enter email is not clickable
- Expected result:The button to enter email is clickable and an input field should appear
Environment:Android 12 
Attachment:fghfmsk.mp4
Lables:email
Severity:major
Priority:medium
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
- Нажать кнопку `Commit changes`
 18. Синхронизировать внешний и локальный репозиторий TXT
 -  `git pull`