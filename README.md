# Applying Cryptography

### Task One: Skytale and Four Square.
Brute-forcing the period length decrypt a scytale message. 
And decrypting a second message encrypted with four square matrices.

### Task Two: Stream Ciphers.
Finding the key to decrypt an English text encrypted with the simple XOR cipher.
Given three valid transaction records decrypted with an XOR cipher and the same,
we forge a new valid transaction record to transfer a large sum is transferred to our account.

### Task Three: Block Ciphers.
Given some plain text and its corresponding cipher text encrypted with an MD5 
three-round Feistel block cipher, figure out the key.

### Task Four: More Block Cipher Attacks.
Implement attacks on block ciphers in CBC and CTR mode using the content leak problem (from repeating cipher text blocks),
the padding oracle attack and a repeated initialization counter.

### Task Five: Hashes and MAC
Modifying two messages to get them to collide with the same hash value. Carefully modify a real transaction record
so the MAC still validates. Given a PRNG and some versions of its state, find the key it was used to produce
and decrypt some text in aec_cbc. 

### Task Six: Feisel and PRNGs
Given corresponding plain and cipher text and the structure of a six-round SHA-based Feisel structure,
find the encryption key and decrypt a second piece of ciphertext.
Given a timestamp-based pseudorandom number generator used to produce a MAC key and an encryption key in turn,
and the timestamp when they were used, figure out these keys and decode the payload they protect.
Decrypt the ciphertext obtained from xoring a sequence_number+command sequence and keystream (from
a given pseudorandom number generator), to get a control sequence that displays a message on the screen.

