This resp includes 14 programs of Cryptography and Network Security labarotary As per VTU/SIT.These are mentioned below.
Questions:
1) Write a program to perform the following using Playfair cipher technique
(i) Encrypt a given message M with different keys {k1,k2,…,kn}. Print key and cipher text pair
(ii) Decrypt the cipher texts obtained in (i) to get back M

2) Write a program to perform the following using Hill cipher:
(i) Encrypt a message M with a given key matrix of size 2X2 and 3X3
(ii) Decrypt the cipher text obtained in (i) by computing inverse of the respective key matrix.

3) Perform encryption and decryption using mono-alphabetic cipher. The program should support the 
following :
i. Construct an input file named plaintext.txt (consisting of 1000 alphabets, without any space or 
special characters)
ii. Encrypt the characters of plaintext.txt and store the corresponding ciphertext characters in 
ciphertext.txt
iii. Compute the frequency of occurrence of each alphabet in both plaintext.txt and ciphertext.txt and 
tabulate the results as follows
Frequency Plaintext character Ciphertext character

4) Write a program to perform encryption and decryption using transposition technique with column 
permutation given as key.

5)Generate and print 48-bit keys for all sixteen roundsof DES algorithm, given a 64-bit initial key.

6)i. Given 64-bit output of (i-1)th round of DES, 48-bit ith round key Ki and E table, find the 48-bit 
input for S-box
ii. Given 48-bit input to S-box and permutation table P, find the 32-bit output Riof ith round of DES 
algorithm.

7) Consider the 128 bits initial key and expand it to 10 different keys each of size 128 bits using AES 
key expansion technique.

8) Consider a message of 16 bytes (128 bits) and perform XOR operation with an initial round key 
[W0, W1, W2, W3] of size 128 bits to generate a state array in AES. W.r.t generated state array of size 
128 bits, perform the following operations in each round.
i.Byte substitution using S-Box 
ii.ShiftRows using left shift 

9) Implement the following with respect to RC4:
i. Print first n key bytes generated by key generation process.
ii. Illustrate encryption/decryption by accepting one byte data as input on the above generated keys.

10) Write a program to generate large random number using BBS random number generator algorithm 
and check whether the generated number is prime or not using RABIN-MILLER primality testing 
algorithm.

11)Implement RSA algorithm to process blocks of plaintext (refer Figure 9.7 of the text book), where 
plaintext is a string of characters and let the block size be two characters. (Note : assign a unique code 
to each plain text character i.e., a=00, A=26). The program should support the following. 
i. Accept string of characters as plaintext.
ii. Encryption takes plaintext and produces ciphertext characters
iii. Decryption takes ciphertext characters obtained in step ii and produces corresponding plaintext 
characters
iv. Display the result after each step.

12)Implement RSA algorithm using client-server concept. Using this illustrate secret key distribution 
scenario with confidentiality and authentication. The program should support the following :
i. Both client and server generates{PU, PR} and distributes PU to each other.
ii. Establish a secret key K between client and server by exchanging the messages as shown in below 
figure. 

13) Compute common secret key between client and server using Diffie-Hellman key exchange 
technique. Perform encryption and decryption of message using the shared secret key (Use simple XOR 
operation to encrypt and decrypt the message.

14)Implement DSS algorithm for signing and verification of messages between two parties (obtain 
H(M) using simple XOR method of hash computation on M).
