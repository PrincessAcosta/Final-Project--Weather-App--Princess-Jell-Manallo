# Princess Jell Manallo
# BSIT 3-2

HOW TO RUN THE CODE:


STEP 1: Open your vs code terminal (ctrl + j)

STEP 2: Run the command "npm start"

: the following will be seen:

- weatherapp@1.0.0 start

- node src/app.js


Server is up and running on port:  3000



STEP 3: Locate the port by typing on your browser "localhost:3000"

STEP 4: Then you will see your code running :>

STEP 5: IMPORTANT NOTE: Make sure to save your work for any changes you've make and refresh the browser otherwise, your code will get an error. 



# QUICK UPDATE: 


- If you get an error after downloading the code, see error below.

  *weatherapp@1.0.0 start
  
  *node src/app.js       

node:internal/modules/cjs/loader:959

  throw err;
  ^

Error: Cannot find module 'express'

Require stack:

C:\Users\christian\Downloads\Final-Project-Weather-App-Princess Jell Manallo\Fnal-Project-Weather-App-Princess Jell Manallo>

    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:956:15)
    
    at Function.Module._load (node:internal/modules/cjs/loader:804:27)
    
    at Module.require (node:internal/modules/cjs/loader:1028:19)
    
    at require (node:internal/modules/cjs/helpers:102:18)
    
    at Object.<anonymous>(C:\Users\christian\Downloads\Final-Project-Weather-App-Princess Jell Manallo\Fnal-Project-Weather-App-Princess Jell Manallo> )
    
    at Module._compile (node:internal/modules/cjs/loader:1126:14)
    
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1180:10)
    
    at Function.Module._load (node:internal/modules/cjs/loader:839:12)
    
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12) {
    
  code: 'MODULE_NOT_FOUND',
  
  requireStack: [ 'C:\\Users\\christian\\Downloads\\Final-Project-Weather-App\\Final-Project-Weather-App\\Princess Jell Manallo\\src\\app.js' ]
  
}


- try deleting the node modules and package-lock json of your code.

- After deleting, run (npm install) on your terminal, this will install a new package-lock json and node modules in your code.

- Then, you may now run (npm start) and continue the process mentioned above. 


