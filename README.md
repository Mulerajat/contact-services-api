# contact-services-api

**Description: **
This API has three methods GET,POST,PUT
GET : It is used to fetect the dat from the datababase This can be done in two ways by passing id as query param to fetch a particular record or passing nothing to fetch all records
POST: It is used to create a new record in databse
PUT It is used to update the records
** NOTE** : The key and ENV has been setup inside which can be externalised while deploying to cloudhub and can be secured using mule-artifact json POSTMAN collection is avaible inside project under postman package  please import that collection and test
SQL queries and table structure also present under project

Steps:

1.Import the application in studio (extract the zip and import it as an normal mule project)
2. Depploy the application
3. FIRST RUN THE post SCRIPT By changing the data inside the body so that it creates a new record to avoid duplicacy . This will give an ID in return which can be later used in    GET method
4. Second run the GET method to FEtch the record using the ID returned in first step
5. Third run the PUT method using the POST body and update some fields so that we can see change using get method again
6. GET meothod can also be used to fetch all records 
