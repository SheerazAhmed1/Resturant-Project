# Resturant-Project
In order to run this project properly you should have installed java developer kit version 11(jdk11) and sql server.
if you have not installed them then here are the links go and download and install them then follow the instrunctions.
jdk11 link (https://www.oracle.com/java/technologies/javase-jdk11-downloads.html#license-lightbox)
sqlserver link(https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
After installing them go ahead and download the project rar file on your dekstop 
Extract that project.rar file
In the project folder there is also rar file named sqljdbc.rar  extract it also. 
Go into sqljdbc extracted folder then there will be a folder name enu click that and in that folder there will be a file named install.txt
Open that file and it will show you how to install sqljdbc
After completing these instrunctions  you need an ide(integrated development environment) to run this project ,install eclipse ide if you have not installed yet.
eclipse IDE download link(https://www.eclipse.org/downloads/packages/release/kepler/sr1/eclipse-ide-java-developers)
Run  the eclipse id and from files tab click import option
click the existing project into workspace and click next
Then click the browse button and go to the location where you have extracted the project and hit select folder button
you will see a project in projects tab named (CombineProjectDSA&DBMS) on its right you will see select all click that and also hit the finsih button at bottom.
After doing this the project should be loaded in Eclipse IDE which will show up in navigator tab on left side of application .
Before executing project we have set build java path in order to run it corectly otherwise it will now run
Right click on project and go to properties 
On the left side there is a name java build path click it 
You will see a tab named libraries click on it if it is not clicked already.
On the right ther is button (add external jars) click it 
It will ask you to give location of file now give it the loaction of sqljdbc which you have extracted already on instrunction line 8,9,10 on this page.
After doing it click apply and close.
Last thing is remaining to run this project is to load the database in Microsoft SQl Server Management Studio.
First you have to connect to sqlexpress server using windows authentication.
Then go to file tab then click open then click  file and give it the location of database file which is .sql file.
now the query file will be opened.
Now go ahead and click alt+x which will execute it there is also a execute button
in 3rd row on the at the top of application.Now last thing go and right click on databses option on left side
and at down in list there refresh option click it and the database will appear in databases section in order to see it you have
to expand the databases and you can do it by clicking + sign.









