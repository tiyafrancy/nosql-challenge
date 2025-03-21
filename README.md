# Module 12 Challenge

To complete this challenge, we are provided with 2 starter code jupyter notebook and one json file.          
First we need to import the data provided in the **establishments.json** file from our terminal. We name the database **uk_food** and the collection **establishments**.         
Use the following code to import the file :      
**mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json**          

Install pymongo using the code : **pip install pymongo**, then **from pymongo import MongoClient** in your jupyter notebook.    
Also **from pprint import pprint** for pretty printing.      


## Part 1: Database and Jupyter Notebook Set Up

Create an instance of MongoClient, mongo = MongoClient(port=27017). Use this to connect to the database.    
We use the functions, **list_database_names(),list_collection_names(),find_one()** in these part of the database and jupyter notebook set up.        
          
## Part 2: Update the Database        
         
Add new restaurant data to the database. Edit, delete, and update the database fields. Change the datatypes and print the results.
Here, we use the functions, **insert_one(),find(),find_one(),update_one(),count_documents(),delete_many(),update_many()** to interact with the database.      
       
## Part 3: Exploratory Analysis          
           
use the **count_documents** to count the number of documents in the results. Display the documents using **pprint**.      
**pd.DataFrame()** is used to convert the results to the pandas DataFrame. To get the required results, the query uses the **$regex,sort(),limit()** operators, and aggregation pipeline is correctly sent to the **aggregate()** method.            


# Acknowledgement    
            
I have done this challenge with the help of my Instructor and some internet searches.         

         


