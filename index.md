# Lab Report 3

For this lab report, I will be discussing the options of the `find` command in bash.

## `find -name`

This command filters find by names of certain files. You can put `*` in between to have certain file names.

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/f148291f-cfba-414c-bc7a-125025ce57fa)

In this example, the find command is filtering through all file names containing `chapter`, having any extension after that and being a file of type `.txt`.

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/9df3d2e4-57b3-4340-acbe-cf5e796975b1)

The above example allows you to use `find -name`, but limiting where it's searched by directory, such as `find (directory) -name (name here)`.

## `find -type`

This command filters find by files of certain types.

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/d2552ca9-bc90-49d1-bd72-39a64e63c271)

In this example, the find command is filtering through all files of type directory, or `-type d`

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/d7ae3cd1-83f7-4082-b24c-1d2125755280)

In this example, the find command is filtering through all non-directory files under the directory `technical/government/Alcohol_Problems/`

## `-and`, `-or`

These are additional operators which you can use in conjunction with the find command, as well its other options. You can use them to either further filter your search results or widen your search results.

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/e0d225d9-162e-4fa0-a0b0-df4136b945b2)

This example looks for any files of type file **and** has the name `chapter*.txt`

![image](https://github.com/Reckswell/CSE-15L-Lab-Report-3/assets/73510375/5b8c1bd0-b58a-489c-a0fe-e2ffd45370a6)

This example looks for any files which are either a directory **or** have the file name `Session*.txt`
