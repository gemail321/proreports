# proreports
Simple Reporting System


System ProReports is available as freeware.
This means that the system can be used for private and professional 
purposes without incurring license fees. 

Available version:

- Windows
- Linux
- AIX (need to contact the author) 


I. Installation of ProReports 

#Windows
1. Uncompress file *.zip to folder 
c:\ProReports.utf8 

...and it all !!! 

#Linux
1. Uncompress file *.gz to folder
/usr/ProReports.utf8 

...and it all !!!

II. Starting ProReports
#Windows

c:\ProReports.utf8\startrepo.bat 

#Linux 

/usr/ProReports/startrepo.sh 

III. Stoping ProReports
#Windows

c:\ProReports.utf8\stoprepo.bat 

#Linux 

/usr/ProReports.utf8/stoprepo.sh 


IV. Log in to ProReports (from local server of ProReports)

Run browser and set url: 

http://127.0.0.1:8080/rep 

Enter:
       login: admin
    password: admin 

V. Sharing ProReports for other users.

In file: 

#Windows
C:\ProReports.utf8\webapp-plus\rep\version.php 

#Linux
/usr/ProReports.utf8/webapp-plus/rep/version.php 


change line:

function __ADRESIP(){ return "127.0.0.1"} ;


to appropriate IP address of ProReports server.

Access: 

http://<address IP of ProReports>:8080/rep 


NOTE! If you use DNS server in function  _ADRESIP  set name of ProReports server, fo example: 

function __ADRESIP(){ return "proreports.domain.com"} ;

Access:  

http://proreports.domain.com:8080/rep
