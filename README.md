# wipro-code
code by sandeep
# pets-curd

Introduction
This a nodejs application for creating,fetching and deleting pets data. 

# How to install
git clone https://github.com/kumarsandy/wipro-code

cd pets

# Install  dependencies
npm install

# Author Sandeep Kumar

# How to run

node index.js

This will run the backend server at localhost:8000. If all is going well, you should be able to access the url following end point from your Postman

For creating new pets : http://localhost:8000/pets/add
For getting pets data : http://localhost:8000/pets/get



#sample for creating pets record 
{
    "name":"Dog",
    "age":2,
    "color":"red"
}
