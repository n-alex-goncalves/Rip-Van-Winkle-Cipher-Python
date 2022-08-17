# Rip van Winkle Cipher Python
A Python program that uses the Rip van Winkle cipher to encrypt and decrypt strings of text made by the user. 

An extract of the [Wikipedia article](https://en.wikipedia.org/wiki/Rip_van_Winkle_cipher) for Rip van Winkle cipher can be found below.
_________________________________

"In cryptography, the Rip van Winkle cipher is a provably secure cipher with a finite key, assuming the attacker has only finite storage.*

*The cipher requires a broadcaster (perhaps a numbers station) publicly transmitting a series of random numbers.*

*The sender encrypts a plaintext message by XORing it with the random numbers, then holding it some length of time T. At the end of that time, the sender finally transmits the encrypted message.*

*The receiver holds the random numbers the same length of time T. As soon as the receiver gets the encrypted message, he XORs it with the random numbers he remembers were transmitted T ago, to recover the original plaintext message."
