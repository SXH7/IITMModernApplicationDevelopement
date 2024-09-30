# 2.2 Efficiency of Encoding

Created: September 30, 2024 4:49 PM
Class: Modern App Developement 1
Week: Week 2

English is probably the most popular common language on the internet. Moreover a lot of European languages use the same character set as english. That’s the reason ASCII was good enough for a long time.

Example: 

Take a text document with 5000 characters in UCS4 encoding (4 bytes/32bits per character)

We end up with 32x5000 bits = 160,000 bits.

Using ASCII encoding (1byte/8bits per character), we take up 8x5000 = 40,000 bits.

Huffman encoding weights the number of bits proportionally to how frequently they occur in the english language (the letter “e” will be the smallest because if occurs more frequently).

### Prefix Coding

Not gonna lie, didn’t understand anything here, just refer to the video ~8 minutes 30 seconds.

### UTF-8

It uses 8 bits for english (via ASCII). Because of this all ASCII documents are compatible with UTF-8 by default.
Other encodings can be used via prefixes. Most common encoding in use today.