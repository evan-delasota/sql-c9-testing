# sql-c9-testing
Following an SQL course through c9.


         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 

sudo yum install mysql-server                               <-- INSTALL FOR MARIADB -->

sudo service httpd start
sudo service mariadb start
sudo mysql -uroot -p


mysqldump -u root -p <db_name> > <export_name>.sql          <-- backup mariadb files -->