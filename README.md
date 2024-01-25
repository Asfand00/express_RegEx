# express_RegEx

STEPS TO RUN SERVER:
1. clone repo into your desired folder
2. open terminal and change directory to your folder, command may vary based on
   preference of terminal. `cd`
3. type command `node index.js` and hit enter
4. terminal will print message that server is running, then go to localhost:3000/user or
   localhost:3000/username to see results

HOW REGULAR EXPRESSIONS IS USED:

Regular expression is used by the following route `user(name)?` indicated in the index.js file
the expression states that if /user is used a default message will be displayed on the page and if 
/username is used the same message will appear. Basically the `(name)?` part is optional and allows for 
matching multiple URL patterns, in this case it allows for two but more can be added. 

   
