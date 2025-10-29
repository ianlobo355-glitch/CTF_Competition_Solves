# Blind Spot

## Challenge Description
![Challenge Description](images/BSDescription.png)

## Solution

In this challenge, We are told to download a file called challenge.zip

After downloading it, there were various folders: File.zip, Junk.docs.

![start page](images/BSFiles.zip.png)

In File.zip, there were 2 more folders: 
Logs.zip and a README.txt 

![files](images/BSLogs.zip.png)

The README.txt contains the sentence: FLAGS HAVE BEEN REDACTED AND ARCHIVED, TRY HARDER.
![message](images/BSMessage.png)

In Logs.zip, there is a syslog.txt file which contains logs of system entries.
![files](images/BSsyslog.png)

The file which grabbed my attention was the Junk.docs. When I clicked on it, a message is displayed saying that the "Archived type is not supported".

![error](images/BSArchiveerror.png)

I googled on how to open such files and found out that 7z tool can be used to extract and open such files.

Without any hesitation, I fired up my terminal and typed the command:
7z x challenge.zip
![command](images/BS7z.png)

The file was automatically extracted and various folders is added on desktop.

Among those folders, there was a Media folder. Upon clicking it, a png file was found , when opened, an image of the flag was displayed.

Since each challenge had 5 attempts, I took the risk and typed the flag in the submit bar.

And thats it, the flag was submitted.

The other folders were like a distraction as most people will go and investigate the folders first. Hence i guessed why the challenge was named as Blind Spot.

