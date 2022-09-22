# Data Modeling

## nosql vs sql

1. SQL databases are best for the complex query intensive environment.

2. NoSQL databases are best for hierarchical data storage.

3. NoSQL databases are like big trees of documents, so they are easy to split up accross multiple servers. SQL databases are like webs of interconnected data that can't easily be split up, so you have to keep it on one server and just make that server as big and fast as you can.

## sql modeling techniques

1. When an entry in one table is related to many in anoter table; they are related by a foreign key that matches a primary key found in another table.

2. It can be useful to create a diagram of the tables and their relationships.

3. A primary key identifies a specific record; it is a unique entry in a table. A foreign key is that same reference wen it is found in another table, referring back to the original table.

## sql vs nosql

1. Keywords are ALL CAPS and parameters are lowercase.

2. Normalization is the process of putting your data into a specific format so that it matches the rest of the data in a table.

3. A one-to-one is each record points to exactly one othe record, such as a person and a social security number. A one to many is when one record is connected to many others, like an artist that has many paintings, but each painting only has one artist. A many to many relation as many connections on either side; for example I have many types of food I like, and each of those foods as many other people that like them as well.
