Caesar Cipher Program

Usage: $python caesar.py ([-d] | [-e] [key]) [filename]

-d: - decrypts a specified file encrypted with a caesar cipher by brute forcing
    - creates a file called decrpyted.txt that stores all possible outcomes

-e: - encrypts a specified file with a caesar cipher, with inputted key
    - creates a file called encrypted.txt that can be decrypted with -d

key: - the numeric value for which to encrypt the file when using the -e option

example:

To encrypt:

$python caesar.py -e 5 to_hide.txt

And then to decrypt:

$python caesar.py -d encoded.txt
