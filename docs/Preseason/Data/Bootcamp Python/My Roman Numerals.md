---
sidebar_label: 'My Roman Numerals Converter'
sidebar_position: 8
---


# My Roman Numerals Converter

> Write a function to convert normal numbers to Roman Numerals.
>
> The Romans wrote numbers using letters - I, V, X, L, C, D, M. (notice these letters have lots of straight lines and are hence easy to carve into stone tablets
> 
> There is no need to be able to convert numbers larger than about 3000.
> (The Romans themselves didn't tend to go any higher)

> Wikipedia says: Modern Roman numerals ... are written by expressing each
> digit separately starting with the left most digit and skipping any
> digit with a value of zero.

> To see this in practice, consider the number 1990.

> In Roman numerals 1990 is MCMXC:

> 1000=M
> 900=CM
> 90=XC

> 2008 is written as MMVIII:

> 2000=MM
> 8=VIII

> See also: http://www.novaroma.org/via_romana/numbers.html

> It will return a string with the roman numeral.

## 🚀 Key Features

- **Convert decimal to roman numerals**: It is required to use the command arguments for giving file paths to the program.
- **Maximum number is about 3000**: Most implementations will start experiencing some errors starting from 4k onwards, but will probably handle numbers such as 3500. Hint: largest gandalf case is 2022
- **Return roman numerals as a string**: The result will be in a string format, only featuring characters I, V, X, L, C, D, M.

## 📝 Task Requirements

Gandalf requirements for this task:
- have a function called my_roman_numerals_converter(n):
- n is an integer type
- n is about 3000, see key features for more clarification

1. **Test 1**: n: 14; expected: "XIV"
2. **Test 2**: n: 79; expected: "LXXIX"
2. **Test 3**: n: 845; expected: "DCCCXLV"

## ⚙️ How the Program Works - hints

This is simple, you've got this (Hint: roman numerals are not base five, they are a bit more like special base ten encoding, so parse it carefully).
(Hint: modulo and integer division operators are your friends in this task).
(Hint: a separate function for converting a base ten digit into a roman tile character would be useful)

## ⚠️ Error Handling

- No errors are expected, if you divide by zero, you probably missed a check somewhere.

## 🛠️ Useful resources for accomplishing this task
* A calculator to check your results. Link : [Roman numeral calculator](http://www.novaroma.org/via_romana/numbers.html)
* Article on base conversion. Link : [Geeks for geeks: Number system and base conversions](https://www.geeksforgeeks.org/number-system-and-base-conversions/)
* Algorithms for conversion to roman numerals. Link : [Medium: Eight algorithms for roman numerals](https://medium.com/@tomas.langkaas/eight-algorithms-for-roman-numerals-b06c83db12dd)