# Credentials Folder

# Important Data about Server

1. Server IPV4: 34.212.246.140
2. Direct link to Website: http://34.212.246.140/
3. SSH Username : ubuntu
4. SSH Key has been provided as "pem" file.

## How to use this information
Direct IPV4 domain will take you to the web host which hosts the github repository. However the direct link to website, will show you the final product.
If you would like to connect to the web server host, do as following:
1. In terminal, move to the directory that has the "New Key Pair.pem"
2. Run this command, if necessary, to ensure your key is not publicly viewable.  chmod 400 "New Key Pair.pem"
3. Afterwards, run this command -> ssh -i "New Key Pair.pem" ubuntu@ec2-34-212-246-140.us-west-2.compute.amazonaws.com
4. This should provide access to the EC2 succesfully.
5. If you would like to find the directory of the git, type cd /var/www/html/

# Important Data about Database
1. Database IP/Endpoint: database-1.cdx4yqkogktl.us-west-2.rds.amazonaws.com
2. Database Port: 3306
3. Database username: admin
4. Database Password: Team06SFSU!
5. Database Name: Main

## How to use this information
If you like to connect to the Database through mysql Workbench fill out as following:
1. Connection Name: Team06
2. Connection Method: Standard(TCP/IP)
3. Hostname: database-1.cdx4yqkogktl.us-west-2.rds.amazonaws.com
4. Port:3306
5. username: admin
6. Password: Team06SFSU!
7. Leave Schema empty
8. Click OK, and launch the MYSQL Database





## The purpose of this folder is to store all credentials needed to log into your server and databases. This is important for many reasons. But the two most important reasons is
    1. Grading , servers and databases will be logged into to check code and functionality of application. Not changes will be unless directed and coordinated with the team.
    2. Help. If a class TA or class CTO needs to help a team with an issue, this folder will help facilitate this giving the TA or CTO all needed info AND instructions for logging into your team's server. 

# Below is a list of items required. Missing items will causes points to be deducted from multiple milestone submissions.

1. Server URL or IP
2. SSH username
3. SSH password or key.
    <br> If a ssh key is used please upload the key to the credentials folder.
4. Database URL or IP and port used.
    <br><strong> NOTE THIS DOES NOT MEAN YOUR DATABASE NEEDS A PUBLIC FACING PORT.</strong> But knowing the IP and port number will help with SSH tunneling into the database. The default port is more than sufficient for this class.
5. Database username
6. Database password
7. Database name (basically the name that contains all your tables)
8. Instructions on how to use the above information.

# Most important things to Remember
## These values need to kept update to date throughout the semester. <br>
## <strong>Failure to do so will result it points be deducted from milestone submissions.</strong><br>
## You may store the most of the above in this README.md file. DO NOT Store the SSH key or any keys in this README.md file.
