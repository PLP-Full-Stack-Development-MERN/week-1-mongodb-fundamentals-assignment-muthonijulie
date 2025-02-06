Step by step instruction on setting up MongoDB:
Download MongoDB on downloads.
Install MongoDB by unzipping the file. If you are using Linux,use the appropriate tool to unzip the file,ark tool or use a command in the terminal(sudo dpkg -i  mongodb-mongosh_2.3.9_amd64.deb).
Check the status of your MongoDB(sudo systemctl status mongod). If it is inactive use the correct command to activate it.Begin with the command,sudo systemctl start mongod then enable using the following command:sudo systemctl enable mongod.
login to MongoAtlas.
Download Mongo Compass and connect it to your database. This allows one to interact and manage their data.
Once the Mongodb compass is installed connect to the default connection.The default connection connects your database on the terminal.
Use the mongo shell in mongoDB compass to add your data.
Ensure that you connect Mongo Compass to Mongo Atlas.
Use queries to display the desired data such as db.books.find() to display all books in the collection.



