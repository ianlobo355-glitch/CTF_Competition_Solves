# Blind Spot

## Challenge Description
![Challenge Description](images/Cookies_description.png)

## Solution
![start page](images/Cookies_start.png)

In this challenge, We are told to download a file called [filename]

After downloading it, there were various folders: File.zip, Junk.docs. 

In File.zip, there were 2 more folders: 
Logs.zip and a README.txt 

The README.txt contains the sentence: FLAGS HAVE BEEN REDACTED AND ARCHIVED, TRY HARDER.

In Logs.zip, there is a syslog.txt file which contains logs of system entries.

The file which grabbed my attention was the Junk.docs. When I clicked on it, a message is displayed saying that the "Archived type is not supported".

I googled on how to open such files and found out that 7z tool can be used to open such files.

Without any hesitation, I fired up my terminal and typed the command:

7z x Junk.docs

The file was automatically extracted and various folders is added on desktop.

Among those folders, there was a Media folder. Upon clicking it, a png file was found , when opened, an image of the flag was displayed.

Since each challenge had 5 attempts, I took the risk and typed the flag in the submit bar.

And thats it, the flag was submitted.

The other folders were like a distraction as most people will go and investigate the folders first. Hence i guessed why the challenge was named as Blind Spot.

