# MIN_RT - minimally readable text

![MIN_RT - preview](https://github.com/hardvvv/MIN_RT---font/blob/main/IMG/preview.jpg?raw=true)

- [X]  Latin alphabet
- [X]  Cyrillic alphabet
- [X]  Special symbol
## Description
The main idea of the font is to create a font that requires minimum of space but remains readable
To use it you need to have a 4х5 matrix, the letters take up all the free space, that is, they don't leave a free row or column, this is not the case for numbers (which have 3x5 matrix and leave the left column empty)
In terms of design I gave priority to the right side, it can be seen on some symbols and special symbols, which parts are more oriented to the right.

## Using the font
Folder `Font Format` contains typical files for installing font on device
But the main idea of the font is minimalism, folder `Binary` contains font record in the form of text file and its copy in binary file (the sequence of characters is saved)

## Logic for writing symbols in binary file
![binary file](https://github.com/hardvvv/MIN_RT---font/blob/main/IMG/How%20read%20binary%20file.jpg?raw=true)

- The sequence of characters is the same as in a text file, one character is written in 5 bytes, and immediately after it are the next 5 bytes for the next character. This format was made to optimize processing on microcontrollers, where this font can be successfully implemented


## Info
- Сreator: HARD_VVV
- License: [`SIL Open Font License (OFL)`](https://openfontlicense.org/)

- Last update: 31.03.2025
- Author link: [`HARD_VVV`](https://hardvvv.carrd.co)


