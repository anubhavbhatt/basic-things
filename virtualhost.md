# Project : YOUR_PROJECT_NAME

## localhost URL : http://<YOUR_PROJECT_NAME>.io

### Vhosts Updation :
Filename: 
`sudo nano /etc/apache2/extra/httpd-vhosts.conf`

```
<VirtualHost *:80>
    ServerAdmin webmaster@localhost
    DocumentRoot "/Users/anubhav/App/<YOUR_PROJECT_NAME>"
    ServerName <YOUR_PROJECT_NAME>.io
    ErrorLog "/private/var/log/apache2/<YOUR_PROJECT_NAME>.io-error_log"
    CustomLog "/private/var/log/apache2/<YOUR_PROJECT_NAME>.io-access_log" common
<\/VirtualHost>
```

### Hosts file Update

`sudo nano /etc/hosts`

`127.0.0.1       <YOUR_PROJECT_NAME>.io`
