# BlockStackNodeServer
TOHACKS Using BlockStack Platform to create Useful Business Architechture


INSTRUCTIONS ON INSTALLATION AND RUNNING ON LOCAL CLIENT: Based on TODO BlockStack DApp Guide
---------------------------------------------------------
 **Note this is a tutorial for Windows 10, modify steps as needed for other workstations**
 
Requirements -
command line
Node.js v10 or higher is recommended the minimum supported version is Node.js v8.
The basic identity and storage services are provided by blockstack.js. 
To test the application, you need to have already registered a Blockstack ID.



The tutorial relies on Node.js and its npx or npm tools. Before you begin, verify you have the correct version of Node.js and its tools installed.

$ node -v
$ node -v
v12.10.0
$ which npm npx
/usr/local/bin/npm
/usr/local/bin/npx


**might have to change environment variables**




Task 1: Install the code and retrieve the dependencies
You can clone the source code with git or download and unzip the code from the repository. These instructions assume you are cloning.

Install the code by cloning it.

 $ git clone https://github.com/ATANKERA/BlockStackNodeServer
Change to directory to the root of the code.

 $ cd blockstack-todos
If you downloaded the zip file, the contents unzip into a blockstack-todos-master directory.

Use npm to install the dependencies.

 $ npm install
 
 
 
 
 ------
 
 
  $ npm run start
  
  
  
     Compiled successfully!

   You can now view bs-todo in the browser.

     http://127.0.0.1:3000/

   Note that the development build is not optimized.
   To create a production build, use npm run build.
   
   
   
   
   
   
   Open your local browser to the http://localhost:3000 URL.
