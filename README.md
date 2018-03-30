# NetworkChat  
  Language used : Java  
  Overview about the project  
  A GUI based program in Java Swing which will allow multiple people/client to connect and send encrypted messages to either a specific connected person or to all which will be all the clients connected at that moment.  
Program is divided into two program one act as the "central server" and another program will be the "client program"
Since normal messages can be “stolen” from the packets during transmission, we will use the RSA algorithm to provide Encryption/Decryption of the message. The way RSA program works is by encoding te entrie message into single numeric value. Those values will be summed up using the ASCII numeric value and decoded back. 
How to run this program 
First run the server driver file which will the "central server". Then once connected run the client driver file which     will display the GUI. At the start of the program each client has to input port number and IP address and create a key pair to send message across the network safe manner. User can input -1 and it will create the keys randomly.
Once, the connection is secure, user can chat across single or with mulitple people. To send message to an individual, the user will select the person's name and then press send otherwise send all for multiple clients.
