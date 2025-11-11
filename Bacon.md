# Bacon (Hard)
Bacon Ciphers are basically binary code with extra steps. You will write a program that take a string as input and output a Super Secret Message $^{TM}$. Our Bacon Cipher is going to use upper and lowercase letters as 1s and 0s respectively (special characters and whitespace will be filtered out).  <br>
It'll be helpful to break this one into steps. 
1. Iterate through the string character by character. If the character is uppercase, store a 1. If lowercase, store a 0. If neither, store nothing and continue.
2. Split your new binary string into chunks of eight (8) characters using the string manipulation method of your choosing (the sample program uses slices and `.split()`, but there are other ways).
3. Translate each string of eight (8) binary characters into ASCII characters (there may be a [python function](https://www.w3schools.com/python/ref_func_chr.asp) for this...)  

### Input
`cOol SecreT PhRasE`
### Output
`Hi`
