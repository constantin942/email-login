### Start "maildev" service in cmd
C:\Users\MI>maildev  
MailDev using directory C:\Users\MI\AppData\Local\Temp\maildev-3200  
MailDev webapp running at http://0.0.0.0:1080  
MailDev SMTP Server running at 0.0.0.0:1025


### Start DemoApplication 
springboot application pattern


### Post request localhost:8080/api/v1/registration
Body  
{
    "firstName": "yuxiang",  
    "lastName": "li",  
    "email": "yuxli@qq.com",  
    "password": "password"  
}  

first time:  
token number

second time:  
{  
    "timestamp": "2022-05-12T20:29:58.006+00:00",  
    "status": 500,  
    "error": "Internal Server Error",  
    "message": "email already taken",  
    "path": "/api/v1/registration"  
}


### Check in localhost:1080
new mail and activate


### Login in localhost:8080
yuxli@qq.com  
password  
Whitelable Error Page 
