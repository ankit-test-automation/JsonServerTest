# JsonServerTest
This is mocked Rest API using json server.

Here we have mocked following Rest APIs
/companies
/Users

## Prerequesites
* Install node js
* Install dependencies by with command 'npm install'

## To start json server, run following command
* npm run json:server

Json server will point to port 3000 by default. To change port, specify different port number in package.json file or you can also change port number with command npm run json:server -p << portnumber >>
  
  
  ## API URLs
  * http://localhost:3000/users
  
  Input Payload Example:
  ```json
  {
    "firstname": "John",
    "lastname": "Doe",
    "companyid": 1,
    "email": "johndoe@gmail.com",
    "age": 40
   }
  ```
  
  * http://localhost:3000/companies
  
  Input payload Example:
  ```json
   {
   "name": "Google",
    "Description": "Google LLC is an American multinational technology company that specializes in Internet-related services      and products, which include online advertising technologies, search engine, cloud computing, software, and hardware."
  }
  ```
  

