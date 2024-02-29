# Homework 1: Node CLI

1. Step

• Create repository named goit-node-cli, clone and initialize the project in it using the npm init command. Install the commander package as a project dependency.
• Place the files (db/contacts.json, contacts.js, index.js) in folder src in the root of the project.

2. Step

• Import the fs (in the version that works with promises - fs/promises) and path modudels in the contacts.js file for workong with the file system.
• Create a contactsPath variable and write the path to the contacts.json file. Use the methods of the path module to compile the path.
• Add asynchronous functions to work with the contacts collection. Use the fs module and its readFile() and writeFile() methods in functions. The corresponding functions must return the necessary data using the return statement. Output to the console shouldn't be carried out in weitten functions.
• Export created functions.

3. Step

• Import the functions from contacts.js to index.js.
• Use function invokeAction(), which receives the type of action to be performed and the necessary arguments. The function must call the corresponding methods from the contacts.js, passing it the necessary arguments. The result of the called function should ne output to the console.

4. Step

Run the commands in the terminal and make sure that the code works properly.

- node index.js -a list

- node index.js -a get -i 05olLMgyVQdWRwgKfg5J6

- node index.js -a add -n Mango -e mango@gmail.com -p 322-22-22

- node index.js -a remove -i qdggE76Jtbfd9eWJHrssH