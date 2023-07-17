(HexaCAPTCHA). CAPTCHAs (Completely Automated Public Turing test to tell
Computers and Humans Apart) are popular ways of preventing bots from attempting to log
on to systems by extensively searching the password space. In its traditional form, an image
is given which contains a few characters (sometimes with some obfuscation thrown in). The
challenge is to identify what those characters are and in what order. In this assignment, we
wish to crack these challenges.

Task is to predict for each image, whether the hexadecimal number in that image is
even or odd. If the number is even, your output should be the string “EVEN” (without quotes)
else your output should be the string “ODD” (without quotes). Take care not to make spelling
or case mistakes. To take the above two numbers as examples, the hexadecimal number 10
is even since it corresponds to the decimal number 16 which is even whereas the hexadecimal
number DECAF is odd since it corresponds to the decimal number 912559 which is odd.
