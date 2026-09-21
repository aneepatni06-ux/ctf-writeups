# 1- Obedient Cat

# Platform :

CyLab Security Academy

## Category :

General Skills / Linux

Approach :

For this challenge,like all the others, I used the CyLab webshell to work with the challenge file.

### 1. Download the challenge file

I copied the URL of the challenge file and used `wget` in the webshell:


wget https://challenge-files.picoctf.net/c_wily_courier/94960d0ab62213382ae31be6ee984974308794c01d681308f5094b9ff30270d6/flag


This downloaded the file into my  current directory.

### 2. Checked the downloaded file

I used `ls` to see the file:


ls


Then I checked what type of file it was:


file file


### 3. Reading the file

I used `cat` to display its contents:


cat file


The flag was displayed directly in the file.

## Solution

The important commands were:


wget https://challenge-files.picoctf.net/c_wily_courier/94960d0ab62213382ae31be6ee984974308794c01d681308f5094b9ff30270d6/flag
ls
file flag
cat flag


The final `cat` command revealed the flag.

picoCTF{s4n1ty_v3r1f13d_9b8fa0bc}



## What I Learned

This challenge introduced me to some basic Linux command-line tools:

* `wget` — for downloading a file from a URL
* `ls` — for listing files in a directory
* `file` — for identifying a file's type
* `cat` — for displaying the contents of a file

It is a simple challenge ,which marks the start of my journey, but it helped me get comfortable using a Linux webshell and working with files from the command line.







