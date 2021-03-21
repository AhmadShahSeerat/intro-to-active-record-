1- Create MVC

2- Create Gemfiles: we put all our gems here, there is one gem which we should put it separately, that is a nested gem which is siatra/active-record/rake this allows our rake -T to work.

3- Create DB, it creates our db, we should have migrations folder, and in it we will have our databases, if our database is not there then we can create one by running the db command

4- Create DB connection to our MVC

5- Create Rakefile: Centralizes our tasks and makes afew things easier. like finding match for a certain path and that have been modified recently.

6- Create Config in which we will have our environment.rb and database.yml file
environment will have all access to all our folder and database.yml is good for whenever we need to rollback this make sure that our programm is compatible with our new version of the programs.

7- git remote add origin git@github.com:AhmadShahSeerat/intro-to-active-record-.git
git branch -M main
git push -u origin main