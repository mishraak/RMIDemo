# RMIDemo

## Commands to follow:

cd src

Command to compile all required files:

javac src/com/amishra/rmiinterface/RMIInterface.java src/com/amishra/rmiinterface/Book.java src/com/amishra/server/Bookstore.java src/com/amishra/client/Customer.java

Command to start server: (remember to change hostname if needed)
java -Djava.rmi.server.hostname=localhost com.amishra.server.Bookstore

Command to start the client:
java com.amishra.client.Customer