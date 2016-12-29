Upload file to dropbox. 
========================

install:
------
  ```
npm install dropbox-uploader
npm install dropbox-uploader -g //for cli
   ```
usage:
------
  use cli command to upload file to dropbox.
  
    dropbox-uploader <localFilePath> <remotePath> <token>
    
      
 ```

 var uploadFile = require('dropbox-uploader');
 uploadFile(localFilePath,remotePath,token,callback);
```
  
Create new app in dropbox and generate  OAuth 2 token, This value is the token. 
  
  
