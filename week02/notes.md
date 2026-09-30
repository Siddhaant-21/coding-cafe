Answers to the first coding-cafe lab assignment 

Siddhaant Lakhi U20260237

1) pwd prints the location I'm currently at, showing the absolute path of the drectory.

2) ls- a shows all(including hidden files) the files within the current directory we are located  at, plain ls does not show the hidden files.

3) drwxr-xr-x 4 hpsiddhaantl hpsiddhaantl 4096 Aug 26 13:04 coding-cafe

the first column is basically the file type and access permissions of the file. The first character(d in this case) depicts the type of file it is(in this case, it is a directory)

4) Directly typing the the name of the directory and the file within it works as it provides a RELATIVE path to where we want to go. We can either type the name of every file we come across beginning from the root(ABSOLUTE PATH) or we can use the relative path. The path mentioned (coding-cafe/week02) is a relative path.

5) The mv command first moved the README-backup.md file that was the duplicate created using the cp command to the week01 file within the coding-cafe directory and then mv helped us rename the file name to old-readme.md from README-backup.md

6) There are 23 folders on my PATH
7) /usr/bin/python3
8) No, the answer was not the same as the next person, which could be bcause of different operationg systems.

9) The shell mentioned the fact that any file with the miss spelt name wasn't found and suggested what it thought we could've meant

Command 'pyton3' not found, did you mean:
  command 'python3' from deb python3 (3.14.3-0ubuntu2)
Try: sudo apt install <deb name>

This error basically indicates that the shell searhed the entire PATH starting from the root to the directory we are in, and did not find any file with the same name as the typo we entered.

10) the .venv file did not appear with plain ls but did with ls -a because plain ls does not show any hidden files. The shell and our system consider any file starting with a '.' as files that are supposed to be hidden.

11) The prompt slightly changed, it now has a (.venv) at the beginning and after 'which python3' command; 

/home/hpsiddhaantl/coding-cafe/.venv/bin/python3

this appeared.

12) No, this is not the same as the resulting prompt in question 7.

The activate command basically updated the path, and made the computer look for the .venv box before anything else.

13) First List

Package Version
------- -------
pip     25.1.1

Second list

Package            Version
------------------ ---------
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
pip                25.1.1
requests           2.34.2
urllib3            2.7.0

The new list has a lot more packages like certifi, charset normalizer, idna, requests and urllib3.

14) The which python3 command now shows the prompt same as that before we had activated the .venv box.

/usr/bin/python3

15) ls -h basically makes the data and descriptors easy to read for humans. I am assuming that means that when we use the ls -l command for the metadata about files and directories, it shows their sizes in direct bits/bytes. ls -h makes it raedable as it shows them in kilobytes, megabytes and gigabytes(hence the k, M and G).

16) Ctrl+C jusrt stops the propmt we were typing and made the cursor enter a new line, Ctrl+D just exited me from the terminal entirely.

