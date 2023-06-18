# hospital-database-management-system (cs207 Project)
If u would like to deploy it just follow this instructions


## step 1 : First of all clone this repository by executing the command
      git clone https://github.com/nunemunthalashiva/hospital-database-management-system.git
      
## step 2: Make sure mysql server is running
       visit this for more details :-)
       https://dev.mysql.com/doc/mysql-startstop-excerpt/5.5/en/windows-server-first-start.html
      
As you can clearly see its running in localhost I havent deployed it in any web server so follow these steps

## step 2 : If you had mysql workbench just follow these instructions(Note: You can also do without workbench there are many tutorials out in the internet please refer it :-)
           
         for more details about workbench visit the link below
         
         https://dev.mysql.com/doc/workbench/en/
         
         Create a database called 'test' (You can keep anything you want and run the sql query named test.sql)
         
         and connect to it in the following way
         
         Please change the following details in app.py
         
         app.secret_key = 'your secret key' // place any thing between quotation marks
         app.config['MYSQL_HOST'] = 'localhost'  // if its localhost just keep this or else specify your host name
         app.config['MYSQL_USER'] = 'root'  // By default its root if ypu would like to change it please see the tutorials
         app.config['MYSQL_PASSWORD'] = 'hmmm' // Its the password when you are entered while installing mysql on your computer
         app.config['MYSQL_DB'] = 'test  // Its the name of database which you are creating I kept its test 
         
  
 ## step 3 : There is nothing to do if you follow above steps and one more thing navigate to your directory via terminal or if you use windows navigate via command-prompt and enter the command
             
         for installing flask and other dependencies visit here
         
         https://flask.palletsprojects.com/en/1.1.x/installation/#installation
         
          "flask run"(without those apphostrophe)
          
          And copy the url and paste it in your browser you can see that website
          
 And last thing to say
 ### images are just brought from web if you feel offended or if it was yours please raise an issue we will be immediately removing it 
 
 Thanks for your intrest in our project :-)

          
          
         
         
         

