# How to Zip a Folder in the Terminal

👇 The terminal command.

```
zip -re output-file.zip folder-name
```


## How to Zip a Folder
1. Open the Terminal.
2. Change directory to the *parent folder* of the folder to be zipped.
3. Enter the following command.

```
zip -r output-file.zip folder-name
```
>Note
>
>`-r` *recursively* includes all files and sub folders. 
>
>output-file.zip = name of the .zip file.
>
>folder-name = target folder to compress.


## How to Zip a Folder with a Password
Adding the `-e` parameter to the command encrypts the created .zip file like so:

```
zip -r -e output-file.zip folder-name
```

## Combining -r with -e
Instead of writing `-r` and `-e` separately, we can combine them like so:

```
zip -re output-file.zip folder-name
```

## Why Is This Useful?
1. Macbooks are missing this functionality to easily add a password to your .zip files.
2. Developers should think about security on a daily basis. 😎🔐
3. Most professionals are able to use the basics of the Terminal.
   
-------------------

@ [MatthewpHarding](https://github.com/MatthewpHarding) 🔗

```Swift
let myLife = [learning, coding, happiness] 
```
### 🧕🏻👨🏿‍💼👩🏼‍💼👩🏻‍💻👨🏼‍💼🧛🏻‍♀️👩🏼‍💻💁🏽‍♂️🕵🏻‍♂️🧝🏼‍♀️🦹🏼‍♀🧕🏾🧟‍♂️
