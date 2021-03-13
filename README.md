# ct-kea-2021-gr19
sql scripts for a database supporting the career-quiz application, aswell as an installation guide to the sql server and workbench

Made by Alexander Broersen, Jacob Berg, Eliza Hansen, Jørn Møller and Christian Nielsen

Make sure to follow the installation guide if you don´t have MySQL Community Server and Workbench installed.

                          --Installation Guide--
In order to run the scrips, you must install the MySQL Community Server as well as the MySQL Workbench. Following link will redirect you to the download page where you can choose which operating system you are downloading for: https://dev.mysql.com/downloads/mysql/.
It is important to have the files for both the Community Server and the Workbench before installing. On the download page there are different ZIP archives to choose from. if you are running on Windows, the ZIP archive "Windows (x86, 64-bit), ZIP Archive Debug Binaries & Test Suite" will download all the files required for the installation. Remember to unzip the archive before starting the installer.

When you have everything installed and you are logged in to your local instance on the Workbench, you can now run the SQL scripts that are attached in this repository. Download the scripts and put them in a folder of your choosing. On the Workbench, click the little SQL-icon with an open folder (located right underneath the "Edit" tab) and select the CTDBDDLscript file. Execute this script by clicking the Lightning-icon. When you have run this script, you do the same thing with the CTDBDMLscript file. Click the little SQL-icon with an open folder (located right underneath the "Edit" tab) and select the CTDBMDLscript file. Execute the script by clicking the Lightning-icon.
                            !!!IMPORTANT!!!
Please note that it is important that you run the DDL-script before you run the     DML-script. When both scripts are executed, you can execute DQL-qeuries on the created tables and views.
