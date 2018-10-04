# Finding secret key used in encryption, where plaintext, ciphertext and IV are given

First download the file and extract it.
The program has a Plaintext and a Ciphertext known, it will find the key. It is trying to encrypt the message using all the keys in the text file and will compare the result with the Cyphertext.

To Compile use: 
````
gcc -o enc project-1.c -std=c99 -lcrypto -ldl 
````
To run the compile code use: 
````
./enc
````
