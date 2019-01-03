# ProxyReEncryption-RSA-AES-
This Java based implementation contains code for Proxy Re-Encryption using RSA+AES. 

The message is encrypted at the Sender level with an AES Key. 

The AES Key is encrypted with the Sender's Public RSA Key. 

The AES Key is then Re-Encrypted at the Server so that it can be decrypted by the Reciever's Private RSA Key. 

After the decryption of the AES Key at the Reciever level the ciphertext is decrypted to obtain the original message.
