# Generate Random String

Use this utility to generate random strings

## Prerequisites

Linx Designer 6.4.3 or higher

## Setup

1. Download the repo
2. Open the `GeneratingRandomString.solution` file in the repository `Linx6` folder

## Usage 

1. Debug the `GenerateRandomString` function
2. Define values for the input parameters
   1. Length (String)
   2. AllowUpperCase (Boolean)
   3. AllowLowerCase (Boolean)
   4. AllowSpecialCharacters (Boolean)
   5. AllowNumbers (Boolean)
3. Start the debugger

## Explanation

1. A string of all allowed characters is created.
2. The Cryptography plugin (`GenerateRandom`) is used to generate a random byte.
3. The byte identifies the location of one character in the string of allowed characters.
4. Each identified character is appended to the end of the return string.
5. The process is repeated until the length of the return string matches the desired length.