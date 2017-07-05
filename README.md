**API**
----
  Manages, shows, modifies, creates, deletes articles; returns json
* **URL**

 https://givemeapi.herokuapp.com/
 
* **Method:**
  
  <_The request type_>

  `GET` | `POST` | `DELETE` | `PUT`  
  
*  **URL Params**

 Header : Content_Type : Application/json    
 Body : Json, if necessary  
 
   **Required:**
 
   `id=[integer] => id of article present`        
   `title=[string]`  
   `body=[text]`   
   
* **Data Params**

https://givemeapi.herokuapp.com/articles/    
https://givemeapi.herokuapp.com/articles/2   
etc.    

* **Success Response:**
    
  * **Code:** 200 <br />   
    **Content:** `json`   
    **Status:** 'SUCCESS'
    
 
* **Error Response:**

  Most endpoints will have many ways they can fail. From unauthorized access, to wrongful parameters etc.  
    * **Code:** 404 <br />   
    **Content:** `json`   
    **Status:** 'ERROR'
    

* **Notes:**

Used faker for faked content, in db:seed   
Checked with postman and curl
