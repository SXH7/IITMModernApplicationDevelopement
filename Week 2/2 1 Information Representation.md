# 2.1 Information Representation

Created: September 30, 2024 4:24 PM
Class: Modern App Developement 1
Week: Week 2

# Information Representation

Computers work only with bits (binary 0s and 1s). Everything in computers, like numbers and letters, can be represented by bits.

## How do we represent text?

Communication in machines usually takes place between machine to machine or human to machine. We need to decide on a standard encoding for communication to be possible. We need to decide what bits represent what characters.

Interpretation of a set of bits is a matter of context. “0100 0001” can mean the decimal number 65 and the letter “A”.

### ASCII

Standardized code for how we interpret specific series of bits. It was a 7 bit code. It had encoding for small and capital letters (a-z, A-Z), numbers (0-9), and special characters (!, @, #, $, etc). 
ASCII did not have encodings for any non english characters.

### Unicode

It allows codes for many more letters. The idea was uncommon languages will not be encoded in unicode because we need to stop somewhere. 

We currently use UCS Encoding (Universal Character Set).

UCS 2: 2 bits per character, max 65,636 characters.

UCS 4: 4 bits per character, 4 billion+ characters