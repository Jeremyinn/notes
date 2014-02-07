# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

* cp (folder and individual files)
Examples:
cp file1 destination_directory


* rm (file and directories)
rm = removes files
rm -r removes directory and contents
Examples:
rm file1 file2 file3
rm -r dir1 dir2

* rmdir
rmdir= removes directories
Examples:
rmdir directory_sample

* ln -s
ln -s makes a soft link of the file which allows you to access that file via another name.
Example:
ln -s myfile mysoftlink

* scp

* pwd
pwd= prints the name of the current directory.
Exmaple:
pwd
output: /cs215


* ls (hidden files and files starting or ending with specific patterns like all files ending in txt or all files starting with the letter b)
ls -a =show all files including hidden files
Example: ls -a
output: folder folder2 .hiddenfolder
ls-l = shows file attributes.

* tar
tar= saves many files to the same destination


## File Transfer

* curl
curl= Curl is similiar to wget except that it writes to the standard output.

* wget
Downloads data to a file from a url.
Example:
wget http://www.yahoo.com
17:15:52 (220.8 KB/s)- 'index.html' saved[3020]


* scp

* rsync

## Pipe tools

* cat
cat = cat displays the text in a file to the screen.
Example:
cat words.txt
This is the text in the file words.txt.

* sort
sort= sorts the information alphabetically or numerically.
example:
sort list_numbers
output: 4 6 7 9

* uniq
uniq= prints the uniq words in a file or can be used to count the duplicates. 
Example: 
uniq text.txt
output: alpha
beta
gamma

* grep
grep= searches for a certain word and can save the words to a file.