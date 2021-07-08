# serverless-api
# lab-18

# Authors - Tek Jones
---

## Deployment task 1 - http://cloudserver-env.eba-y7gp6nkr.us-west-2.elasticbeanstalk.com/
## Deployment task 2  - http://node-express.eba-y7gp6nkr.us-west-2.elasticbeanstalk.com/
---

### Feature Tasks
Create a single resource REST API using a domain model of your choosing, constructed using AWS Cloud Services



### Database
- DynamoDB


## Routes via API Gateway

### POST
  /people
    * Given a JSON body, inserts a record into the database
    * returns an object with ID

### GET
  /people
   * returns an array of objects with all people in the database

  /people/ID
   * returns an object representing on record by its ID

### PUT
  /people/ID 
  * given JSON body and a ID, updates record in database
  * returns an object with ID

### DELETE
  /people/ID 
  * given ID deletes matching record from database
  * returns an empty object


## UML
![UML](uml-lab18.png)