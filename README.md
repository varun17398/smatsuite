# SmatSuite
PHP task of smatsuite backend developer

This repo is full code for the task that you have assigned me.

The core code is in a file called `Api.php` where all the endpoints have been created as asked. The Model for data manipulation from database is named as `Contact_Model.php`.

1. addContact Endpoint - 
    
    Takes 5 parameters which are firstname, lastname, email, mobile_number and data-store. The request format is attached as a image in the mail sent.
    
2. getContact Endpoint - 

    Takes 2 parameters which are contact_id and data-store. On success it will show the details for the fetched contact details.
    
3. updateContact Endpoint - 

    Takes 4 parameters which are email, mobile_number, contact_id, data-store. contact_id parameter tells it which contact to be updated. The request format is attached as a image in the mail sent.
    
4. deleteContact Endpoint - 

    Takes 2 parameters contact_id and data-store. On success will delete the respective contact based on the given contact_id.
    
# Database Schema

The name of the database is meant to be contact_details and the name of the table to be contact. Schema is as follows - 

  Contact table consists of 5 columns contact_id(integer and auto incremented), firstname(varchar not null), lastname(varchar not null), email(varchar not null), mobile_number(integer not null).
  
  There is an attached SQL file of the mentioned database so that you can directly import it on your local mySQL server and run it.
  
# Run the project

I ran the project on local PHP server using command `php -S 127.0.0.1:8080` after that I setup database on local mySQL server.

All the endpoints can be accessed as `http://localhost:8080/api/[endpoint name]` with passing required parameters. mySQL server needs to be running in order to perform operation on the database.

CRM endpoint is already mentioned in code along with API key. So you can access them by the same.

First extract the given zip file which will give you one file named `contac_details.sql` which is the given sql file for you to import and a folder named `myApp`. To run the project go into myApp and then run the PHP local server as mentioned above.

For you reference images of all the endpoint with required body and response has been attached with sent mail. Please check.

For any more details and clarifications you can revert back to me on - 

Email - saivarunsvrn@gmail.com
Phone - +919915130303
