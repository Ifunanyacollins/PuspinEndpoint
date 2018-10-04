# travelEndpoint

Puspin is a fictional transport company,located in the heart of Ebonyi state,Nigeria.

## Get Started
 You can clone this project or make a pull request , if you are just intrested to see the end result please see
 [Puspin](http://puspin.herokuapp.com/hook)

 ### Prerequisites
 The core dependencies for this project are
  - cors
  -  express
  - express-graphql
  - graphql
  -  mongoose
  
  ### Installing
  Runnig this command will auto install all dependencies used for this project
 ```
 
 npm install 
 nodemon app.js or node app.js //to start server

 
 ```
 In your browser go to  http://puspin.herokuapp.com/hook
 
 > if you cloned or pulled a request ,I am using [Mlab](https://mlab.com) mongdb, you are to change process.env.dataBase to your own database url.
 >
 **Queries**
 
  For all avaliable Bus 
  fields [ name, depart_time,id,terminalId]
   ``` 
     {
     buses {
       name
        depart_time
        .....
        }
        
     }
   ```
  
  For a single Bus 
  fields [ name, depart_time,id,terminalId]
  ```
  {
  bus(id:"1233489-fihugymkjbhh-37tgyd6eytr6"){
   name,
   id
   .....
 }
  }
  ```
  
  
 
 
