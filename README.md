# Php No AlphaNumeric Obfuscate Tool!

<p align="center">
  <img src="https://i.imgur.com/hdfx2sh.png" height="35%" width="35%">
</p>


## Introduction

**<p align="center">🎉 This is the tool that help you create php function in no-alnum style 🎉</p>**

## How to use

🕵🏾 Very first command: 
```css
git clone https://github.com/tsug0d/PhpNoAlnum.git
```

😎 Go to its directory:
```css
cd PhpNoAlnum
```

🤘 Then:
```css
python php_noalnum.py --file <input_file_path> --out <out_put_file_path>
```

🤖 Example:
```css
python php_noalnum.py --file test4_system.php --out test4_output.php
```
<img src="https://i.imgur.com/r1s2vOp.png" >
<img src="https://i.imgur.com/8OVrHJ0.png" >

## Rules to follow

* Input file content must follow Correct Syntax php code
* This tool only works with php function
```css
function_name();
function_name(function_value1,function_value2,....);
function_name('aaaa');
```
* No PHP Comment (`#`, `/* */`, `//`) in code
