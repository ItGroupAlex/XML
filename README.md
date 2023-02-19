# XML

 21. Создать внешний репозиторий c названием XML.  
	*создаем через веб-интерфейс репозиторий XML  
 22. Клонировать репозиторий XML на локальный компьютер.  
	$ git clone git@github.com:ItGroupAlex/XML.git  
 23. Внутри локального XML создать файл “new.xml”.  
	$ touch new.xml  
 24. Добавить файл под гит.  
	$ git status  
	$ git add .  
 25. Закоммитить файл.  
	$ git commit -m "Added file"  
 26. Отправить файл на внешний GitHub репозиторий.  
	$ git push origin  
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
	$ vim new.xml  
	`*i`
```
<xml>  
        <?xml version="1.0" encoding="UTF-8"?>  

<man="Alex">  
        <film>Список Шиндлера</film>  
        <name>Алексей Х.В.</name>  
        <age>38</age>  
        <pets>1</pets>  
        <salary>2000</salary>  
</man>  

</xml>  
```
	*Esc  
	*:x  
	*Enter    
 28. Отправить изменения на внешний репозиторий.  
	$ git status  
	$ git add .  
	$ git commit -m "Redact new.json"  
	$ git push origin  
 29. Создать файл preferences.xml  
	$ touch preferences.xml  
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
	$ vim new.xml  
	`*i`  
```
<xml>  
        <?xml version="1.0" encoding="UTF-8"?>  

<man="Alex">  
        <film>Список Шиндлера</film>  
        <serial>Побег</serial>  
        <food>Суши</food>  
        <season>Лето</season>  
        <country>Мальдивы</country>  
</man>  

</xml> 
```
	*Esc  
	*:x  
	*Enter  
 31. Создать файл skils.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
	$ vim skils.xml  
	`*i`  
```
<xml>  
        <?xml version="1.0" encoding="UTF-8"?>  

<man="Alex">  
        <skil1>English</skil1>  
        <skil2>QA</skil2>  
        <skil3>Python</skil3>  
</man>  

</xml>
```
	*Esc  
	*:x  
	*Enter  
 32. Сделать коммит в одну строку.  
	$ git status  
	$ git add .  
	$ git commit -m "Redact new.json"  
 33. Отправить сразу 2 файла на внешний репозиторий.  
	$ git push origin  
 34. На веб интерфейсе создать файл bug_report.xml.  
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
```
<xml>  
        <?xml version="1.0" encoding="UTF-8"?>  

<bag="Login">  
        <id>1</id>  
        <Title>The buttom <Login> must redirect to login form</Title>  
        <ER>buttom <Login> must redirect to login form</ER>  
        <AR>error</AR>  
        <Severity>Critical</Severity>  
        <Priority>High</Priority>  
</bag>  

</xml>  
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 38. Синхронизировать внешний и локальный репозиторий XML  
	$ rm -rf xml  
	$ git clone git@github.com:ItGroupAlex/XML.git  
