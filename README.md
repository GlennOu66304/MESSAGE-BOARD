1.add the emoj into the board  
Command + Control + Space shortcut  
 [The Power of Emojis in Marketing and How to Use Them Efficiently With These Little-Known Keyboard Shortcuts](https://buffer.com/library/emojis-keyboard-shortcut-mac-windows/)   

 ## POST MAN  
 2.Postman use in the app: [Download Postman](https://www.postman.com/downloads/)  
 3.CTRL + C to kill the post man connection;  
 4. if you meet the bug"npm ERR! missing script: dev":  
 Please make sure that your current folder is at the server folder, try to use the"cd /Users/zt/MESSAGE-BOARD/server' to get back to the server folder, then install the nodemon and run npm run dev.  
 [npm run dev reports an error: missing script:dev](https://www.programmersought.com/article/39854586248/) 

       
## video resource:  
[Newby Tuesdays - Build a full stack message board with Node/Express/MongoDB/Vue.js/Bootstrap](https://www.youtube.com/watch?v=2xIoWm08SBM&list=PLul9aZOSt5CPetBw-Nl_6PzdgG-bBYL75&index=4&ab_channel=CodingGarden)  
Source code1:[message-board-client](https://github.com/CodingGarden/message-board-client)    
source code2:[message-board-server](https://github.com/CodingGarden/message-board-server) 


## Boot strap and bootswatch:

1.You need to open the bootstap.min.css into the new file in the browser, then copy the address;  
[Cyborg](https://bootswatch.com/cyborg/)  
[min.css](https://bootswatch.com/4/cyborg/bootstrap.min.css)  

2. run the project in the browser:
```
zt@ztdeMacBook-Air MESSAGE-BOARD % cd client
zt@ztdeMacBook-Air client % npm run serve
```
3.then put  this link into the index.html file under the client folder  
```
<link rel="stylesheet" href="https://bootswatch.com/4/cyborg/bootstrap.min.css ">
```
Resource List:  
[bootstrap](https://getbootstrap.com/docs/4.5/components/list-group/)  
[Cyborg](https://bootswatch.com/cyborg/) 

### vue cli conflic solving:
Go back to the @vue/cli@3.0.0-beta.9 to bnegin our project building:  
1.install @vue/cli@3.0.0-beta.9 package: npm i @vue/cli@3.0.0-beta.9
[npm i @vue/cli@3.0.0-beta.9](https://www.npmjs.com/package/@vue/cli/v/3.0.0-beta.9)  
2.install cmd-shim: npm i cmd-shim@3.0.2  
[npm i cmd-shim@3.0.2](https://www.npmjs.com/package/cmd-shim/v/3.0.2)
[Error: Cannot find module 'cmd-shim'](https://stackoverflow.com/questions/51050688/cannot-find-module-missing-modules-557)  
[Vue cli Getting Started](https://cli.vuejs.org/)  
3.npx @vue/cli@3.0.0-beta.9 create client

```
npm install -g @vue/cli@3.0.0-beta.9 

npm i cmd-shim@3.0.2

npx @vue/cli@3.0.0-beta.9 create client
```

If you meet the issue with TypeError: api.injectImports is not a function, then you need to upgrade the vue cli, then create the project:
```
npm update -g @vue/cli

vue create client
```  
Vue CLI v3.12.1  
[Upgrading](https://cli.vuejs.org/guide/installation.html)  
[TypeError: api.injectImports is not a function](https://stackoverflow.com/questions/50703003/updating-vue-cli-global)  

## References:  
[Newby Tuesdays - Build a full stack message board with Node/Express/MongoDB/Vue.js/Bootstrap](https://www.youtube.com/watch?v=2xIoWm08SBM&list=PLul9aZOSt5CPetBw-Nl_6PzdgG-bBYL75&index=4&ab_channel=CodingGarden)  
Source code1:[message-board-client](https://github.com/CodingGarden/message-board-client)    
source code2:[message-board-server](https://github.com/CodingGarden/message-board-server) 