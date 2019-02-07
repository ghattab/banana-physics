# Banana Physics
Banana physics is a set of print-ready A7 cards to learn 14 of the most used physical constants in a fun way!

![](https://raw.githubusercontent.com/ghattab/banana-physics/master/banana-physics-poster.png)

Each card design relies on a humoristic and relatable depiction of a banana in the context of the physical constant.
The information is presented using redundant visual encoding, emphasis, repetition, and alternate representation of the constant's value.
Visual encodings are shown under a *Reference banana* card and are listed in detail below.

## Visual encodings
For each constant [position on card] (color/symbol):
* __Category__ [top left + back middle]: Exact (blue/square), Computed (orange/circle), Measured (red/triangle)
* __Scientific notation__ [middle]: 6 digits number and an exponent (highlighted black background)
* __Hexadecimal value__ [middle]: information compression for each 6 digits number (highlighted category background)
* __Exponent__ [top right]: value and sign of exponent as the card number (category)

### Hexadecimal conversion
As it is sometimes hard to remember the scientific notation of some constants, the hexadecimal form serves as an alternative to remember the 6 digits number. As a means for data compression, it reduces the amount of digits to alphanumeric characters. The conversion algorithm and an example conversion from hexadecimal to decimal are provided below:
```
7DE is a hex number (zero based, 7DE: E location is 0, D location is 1 and the 7 location is 2)
7DE = (7 * 162) + (13 * 161) + (14 * 160) 
7DE = (7 * 256) + (13 * 16) + (14 * 1) 
7DE = 1792 + 208 + 14 
7DE = 2014 (in decimal number)
```
* Get the decimal equivalent of hex from table
* Multiply every digit with 16 power of digit location 
* Sum all the multipliers.

## Sources
All reported values are in the International System of Units.

## License
```
Licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. 
To view a copy of this license, please refer to the LICENSE file.

```
