# Broken

## Challenge Description
![Challenge Description](images/description.png)

## Solution

In this challenge, We are given a file which could not be extracted.

![error](images/error.png)

I tried to extract using 7z tool, but still got an error

![error_7z](images/error_7z.png)

Finally, I used the xxd command to check the header of the file and VOILA!!! The flag was found. Also, yhe file header was not proper. Now I know why I cant open and extract the file.

![flag](images/flag.png)


