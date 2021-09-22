# LENNAH
A simple static site generator made in C++.

### Why is this called LENNAH?
It's just the name I randomly got from a character and liked it.

<img src="https://imgur.com/ThRo0GT.png" width="150" height="150">

## Installation and How to Use
1. Clone the repo
2. Get the absolute path of the LennahSSG.exe (e.g. ***C:\Users\\\<Your Name>\LennahSSG\Debug\LennahSSG.exe***)
3. Open the console and enter the path followed by an argument

## Arguments
Argument | Description
------------ | -------------
`-h`, `--help` | Displays the help information
`-v`, `--version` | Displays the current version number
  `-i <PATH>`, `--input <PATH>` | Converts txt file(s) at the `<PATH>` to html. The output will be in a folder called `dist` in the current directory (So make sure you know what directory you are calling the exe from).

## Features
- Converts text or markdown files into a formatted html file
- Takes the first line of the text file and sets it as the title and gives it a header format
- Can recursively go through deep folders to find txt files
- Supports markdown syntax for **bold** and *italics* (text found in an .md file with ```**text**``` or ```__text__``` syntax will be made **bold**, text found with ```*text*``` or ```_text_``` syntax will be *italicized*.

## Example
```
C:\Users\User\LennahSSG\Debug\LennahSSG.exe -i "Silver Blaze.txt"
```
This will result in this sample html page:
http://joshuali7536.github.io/LennahSSG

## Example 2
```
C:\Users\User\LennahSSG\Debug\LennahSSG.exe -i Scene1.md
```
This will result in this sample html page:
https://gusmccallum.github.io/

