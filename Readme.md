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

The `GeneratingRandomString` function creates a string of all allowed characters using the booleans for upper case, lower case, special characters and numbers passed into the function.

The `GenerateRandom` function from the Cryptography plugin is used to generate a random byte.

The byte is used to pick charaters from the allowable characters set by using their index.

Each random character selected using this method is appended to the end of the string of random characters.

The process is repeated until the length of the return string matches the desired length.