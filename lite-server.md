Outcomes :                                                                                                                             
 Add package.json to the project folder . package.json contains configuration of the project.                                              1. We need to configure the dependencies and info into the package.json                     
2. To do so type command **npm init** after navigating to the folder in cmd.                                                              
3. You will get series of queries, entry point is the starting page of the web page or app.                                                              
4. We add lite server , to do so type **npm install lite-server --save -dev** . To save this info into package.json                               
5. To enable the lite-server to start on invoking , we add fields to the package.json : "start":"npm run lite","lite":"lite-server"                               
6. Go to cmd , type *npm start*                                                                                                                                                           
7. This starts lite server and opens a browser, now whatever changes you do the files and save will automatically reflect without having                                                              
  to refresh the browser.                                                                                             
8. Now, if you want to mirror these added and modified files to remote git repository, we prefer not to these lite-server ,npm modules
    because they are additional features we just wanted.                                                                                             
9. To do so, we add a file to the project folder named **.gitignore** containing **node_modules**                                                              
10. Now we can add .  and commit and then push to the online git , and the node modules wont be added.                               
