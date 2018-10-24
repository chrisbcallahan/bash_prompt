# bash_prompt

# Project 4

Chris Callahan (811-264-461)
John Zay(811-337-298)

## Instructions

To clean my code (i.e., remove any compiled files), type:

```
$ make clean
```

To compile my code, type:

```
$ make
```

To run my code (after compiling it), type:

To Run:
1: $ ./1730sh

Once Running:
2: $ cat file.txt
3. $ cat file.txt | grep // > out.txt
4. $ help [command]
5. $ cd [path]
6. $ exit
7. $ export NAME[=WORD]
8. $ fg JID
9. $ jobs
10. $ Any Regular Bash Command


## Reflection
This project required me to parse text from standard input while looping continuously like a bash prompt. I had to run the program using fork and exec system calls to spawn new processes.  I also had to implement built-in commands (cd, help, exit, bg, fg, export, jobs, kill) into my program for robustness. We have added status changes in for the final version, background tasks have also been added, we have completed I/O redirection and other various requirements.
