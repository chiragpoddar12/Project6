IP address : 13.126.63.118
SSH Port : 2200
URL : http://13.126.63.118/

Config changes :
I used lightsail amazon web service as a virtual web server.
Created ssh keygen for the user ubuntu and grader.
Disabled login with password (nano /etc/ssh/ssh_config)
Provided sudo permissions to user grader
configured firewall to accept connections for SSH(2200), HTTP(80)
Set local timezone to IST
Installed and configured Apache to serve a python mod_wsgi application
Installed Postgresql

Third Party Softwares : Google Login


Login : ssh grader@13.126.63.118 -p 2200 -i ~/.ssh/project5
Passphrase to Login : passphrase
