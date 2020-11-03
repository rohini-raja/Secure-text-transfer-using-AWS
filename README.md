# Secure-text-transfer-using-AWS
Encryption and Decryption using AES and file transfer using Diffie-Hellman exchange. Hosting using AWS. 
1. Creating Amazon Web Services(AWS) Account and EC2 instance.
2. EC2 instance provides a public IPV4 address that is used for accessing the website.
3. The port range displayed in EC2 displays the port number which will be used for the connection.
4. Creating an S3 bucket and upload the source code as a zip file.
5. Extracting the source code from the S3 bucket into the system.
6. Download the public key from AWS EC2 and generate a private key using PuttyGen.
7. Hosting EC2 instance using PUTTY with the private key generated from PuttyGen.
8. Access web application using PUTTY.
9. Register as a user and store the generated private key.
10.Download the public key of the respective user(sender/receiver).
11. Run GUI application and encrypt/decrypt the message with the help of public and private keys that have been downloaded earlier.
12. Upload the encrypted/decrypted file to the cloud which is accessible to other users.
