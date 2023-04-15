# MongoDB-Learning

Datas area stored in a form of collection

Collection is nothing but the JSON - Javascript Object Notation

{
name:"Akash",
Id:10,
address:{
country:"India",
state:"Tamil Nadu"
},
hobbies:["listing audio books", "cricket"]
}


In mongoDB the JSON is stored in aformat of BSON-Binary Object Notation

Why MongoDb?

There is no need for Normalization 

Normalization 
      In Sql the tables are seperated from one another and joined using the primary keys to have a decent data storage.
      In Nosql the data are stored in Json so no nned of Normalization
      
      
There is no forced schema for all the document. Object can be differ from one other


COMMANDS

1 show dbs - show all database that are created
2 use dbname - it allows us to use or work on the selected db
3 db.dbname.insertOne({name:"Akash",
                         address:{
                         state:"Tamil nadu"
                         }) 
                         })




