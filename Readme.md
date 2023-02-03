# Generate Random String

Use this utility to generate random strings of any length

## Prerequisites

Linx Designer 6.4.3 or higher

## Setup

1. Download the repo
2. Open the `GeneratingRandomString.solution` file in the repository `Linx6` folder

## Usage 

1. Debug the `GenerateRandomString` function
2. Define the values for the input parameters
   1. Length (String)
   2. IncludeUpperCase (Boolean)
   3. IncludeLowerCase (Boolean)
   4. IncludeSpecialCharacters (Boolean)
   5. IncludeNumbers (Boolean)
3. Start the debugger

## Explanation

1. A string of all allowable characters is created.
2. The Cryptography plugin (`GenerateRandom`) is used to generate a random byte.
3. The byte is used to pick characters from the total set by using their index.
4. Each selected character is appended to the end of the string of random characters.
5. The process is repeated until the length of the return string matches the desired length.