## EX 13 : IMPLEMENTATION OF MESSAGE AUTHENTICATION CODE(MAC)


## AIM:

To implement a Message Authentication Code (MAC) using a shared secret key and a hash function to verify the integrity and authenticity of a message.


## ALGORITHM:

1.	Choose a shared secret key that will be known to both the sender and the receiver.
2.	Define the message that needs to be authenticated.
3.	Concatenate the message and the secret key to form a new string.
4.	Apply a hash function (e.g., simple XOR-based hash or any secure hashing function like SHA) to the concatenated string to generate the MAC.
5.	Send the message along with the generated MAC.
6.	For verification, the receiver uses the same shared key, concatenates it with the received message, and applies the hash function to generate a new MAC.
7.	Compare the generated MAC with the received MAC. If they match, the message is authentic; otherwise, it has been tampered with.


## PROGRAM:

## OUTPUT:
 
## RESULT:

The Message Authentication Code (MAC) was implemented successfully, allowing the verification	of	message	integrity	and	authenticity	using	a	shared	secret	key.
