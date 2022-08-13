# Password Protect .zip Files
*The solution*

```
zip -re output-file.zip folder-name
```


## Zip A Folder
**Open the Terminal** with the directory set to the *parent folder* of the folder needing to be zipped

```
zip -r output-file.zip folder-name
```
👉 Note: **Always** include `-r`. It means *recursively* include all files and sub folders. 

*output-file.zip = name of the .zip file created.*
 
 *folder-name = target folder name to zip.*


## Zip A Folder + Password
**Open the Terminal** with the directory set to the *parent folder* of the folder needing to be zipped

```
zip -r -e output-file.zip folder-name
```
👉 Note: **Always** include `-e`. It means *encrypt* which sets the password

Enter the password and press enter.
You will be prompted to re-enter your password and press enter. 

## Merge `-r` With `-e`
**Open the Terminal** with the directory set to the *parent folder* of the folder needing to be zipped

```
zip -re output-file.zip folder-name
```
🥳 It works! 

##Why Is This Useful?
2. Macbooks are missing this functionality to easily add a password to your .zip files.
3. Developers should think about security on a daily basis. 😎🔐


# 🤷🏼‍♂️

Thanks 

for reading

@[MatthewpHarding](https://github.com/MatthewpHarding)

*written for the `Swift` community*

```Swift
let myLife = [learning, coding, happiness] 
```
### 🧕🏻👨🏿‍💼👩🏼‍💼👩🏻‍💻👨🏼‍💼🧛🏻‍♀️👩🏼‍💻💁🏽‍♂️🕵🏻‍♂️🧝🏼‍♀️🦹🏼‍♀🧕🏾🧟‍♂️