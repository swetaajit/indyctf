### Baby_IR

An IR Communication was sniffed between two people. The data was a pile of binary digits. Analyze the data sniffed and use them in the circuit and get a "meaning full" flag. (Data contains junk values too.)

111111010101000010101111

111111011001010001111111

111111010000100011110111

000111011001010001111111

111111011011000001001111

010111001001010001110111

111111010001100011100111

010111001011010101110011

111111011000000001111111




Here from the code of the given simulation ,one can understand that some of the hexadecimal cases corresponds to the bits of the flag.
Some of the given binary numbers are just junks.So  using a hex to binary converter  you find the hexadecimal equivalent of the these binnary numbers.
Compare these conversions with the hexadecimal cases in the simulation code .The ones that are found will be the bits of the flag you are searching for.
For example the fisrt binary number gives you the hexadecimal equivalent FD50AF ,which is part of the code .
This gives you the flag

![image](https://user-images.githubusercontent.com/92258994/176898704-97f809d5-4c9d-4f42-a50c-e8efcb965a42.png)
ictf{whrs_m4_f1aG}

