# Homework1_ETH-Devs101
Every cryptographic hash function is a hash function. But not every hash function is a cryptographic hash.

A cryptographic hash function aims to guarantee a number of security properties. Most importantly that it's hard to find collisions or pre-images and that the output appears random. (There are a few more properties, and "hard" has well defined bounds in this context, but that's not important here.)

Non cryptographic hash functions just try to avoid collisions for non malicious input. Some aim to detect accidental changes in data (CRCs), others try to put objects into different buckets in a hash table with as few collisions as possible.

In exchange for weaker guarantees they are typically (much) faster.

I'd still call MD5 a cryptographic hash function, since it aimed to provide security. But it's broken, and thus no longer usable as a cryptographic hash. On the other hand when you have a non cryptographic hash function, you can't really call it "broken", since it never tried to be secure in the first place.

source: Stackexchange-What is the difference between a Hash Function and a Cryptographic Hash Function?
