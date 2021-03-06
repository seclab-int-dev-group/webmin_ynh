# WebMin package installation for YunoHost


[![Integration level](https://dash.yunohost.org/integration/webin.svg)](https://dash.yunohost.org/appci/app/webmin)  
[![Install Webin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=webmin)
<br><br>

> *This package allow you to install Webmin quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

**Note:** This app has **root** access which can change core things in the system, thus **breaking the YunoHost**. Use it carefully and read the [documents](https://doxfer.webmin.com/Webmin/Main_Page) two times before changing values.

## Webmin
[Webmin](http://www.webmin.com/index.html) is a **web-based** interface for system **administration** for Unix. Using any modern web browser, you can setup user **accounts**, **DNS**, **file sharing** and much more. Webmin removes the need to manually **edit Unix configuration** files like **/etc/passwd**, and lets you manage a system from the **console or remotely**. 

## Links
- [Yunohost project](https://yunohost.org)
- [Webmin](http://www.webmin.com/)
- [Webmin source code at Github](https://github.com/webmin/webmin)

## Important points
- Only **root** (system user) can connect 
- Webmin will **update itself** when system updates are run. So no need to **run upgrade script** once installed.
- Only **user** given permission at time of the installation can **access** the Webmin 
- Installation can only be done on **root path**. Eg. webmin.domain.tld 
- No **multi-instance** for webmin as it is a system integrated app 



