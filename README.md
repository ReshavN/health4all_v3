# Health4All

Softwares to be installed
    - WAMP / XAMPP Server

Steps to be followed : 
    1. Create a Github account .
    2. Fork (health4all_v3) from https://github.com/UCDS/health4all_v3.
    3. Clone health4all_v3 from your forked respository to your system 
    4. Move this app to either www folder if you are using WAMP, or to htdocs in case of XAMPP server
    5. Navigate to http://localhost/phpmyadmin/index.php  and create a new database with name 'health4all'.
    6. Import the sql file from health4all_v3/db/health4all.sql into 'health4all' database created in above step.
    7. Run the script SET GLOBAL sql_mode=''; in phpmyadmin sql editor
    8. Open health4all_v3 app in browser (http://localhost/health4all_v3/) and login with below credentials
        credentials-
                username  : admin
                password  : password  

Note :  To hide the errors  , change environment from 'development' to 'production' health4all_v3/index.php line number 20 
    
 