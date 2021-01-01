# key-value-data-store
 
  /* Initialize the DataStore with default storage location*/
  DataStore myDataStore = new DataStore();
   /*Initialize the Datastore with storage location*/
  DataStore myDataStore = new DataStore(String filepath);
  /*Method to create an element in DataStore*/
  myDataStore.create(String key, JSONObject value);

  /*Method to create an element in DataStore*/
  myDataStore.create(String key,JSONOject value,int timeToLive);
  /*Method to read an element in DataStore*/
 myDataStore.read(String key)
  /*Method to delete an element from DataStore*/
 myDataStore.delete(String key)





       CREATE
 
Create operation successful
Operation failed due to key already available 
Create operation successful 
Operation failed due to key length exceeded the limit(32chars)

   READ

{"firstName":"Moulika","lastName":"Sammidi","address":"Vizag","age":"21"}
{"firstName":"Moulika","lastName":"Sammidi","address":"Vizag"}
Operation failed due to key not available 
Operation failed due to key length exceeded the limit(32chars)

   DELETE
Operation failed due to key not available 
Record deletion successful 
