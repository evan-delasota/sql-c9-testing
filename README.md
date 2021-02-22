# sql-c9-testing
Following an SQL course through c9.


         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 

sudo yum install mysql-server                               <-- INSTALL FOR MARIADB --><br />

sudo service httpd start<br />
sudo service mariadb start<br />
sudo mysql -uroot -p<br />


mysqldump -u root -p <db_name> > <export_name>.sql          <-- backup mariadb files --><br />

testing git profile settings<br />

CRUD:
    Create -    CREATE<br />
    Retrieve -  SELECT FROM WHERE<br />
    Update -    UPDATE SET WHERE<br />
    Delete -    DELETE FROM WHERE<br />
    
When updating / deleting, use SELECT to target the data in question before executing any UPDATE / DELETE command, 
as there are no take-backsies. Unless your using version control and constantly backing up your database. (pls do) <br />