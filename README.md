# Finding secret key used in encryption, where plaintext, ciphertext and IV are given

First download the file and extract it.
The program has a Plaintext and a Ciphertext, it will find the key in brute forcing all the key in the text file.

To Compile use: 
````
gcc -o enc project-1.c -std=c99 -lcrypto -ldl 
````
To run the compile code use: 
````
./enc
````
