## Expected output for a child normal exit
```
Hello from the child process!
The parent process ID is 144420
The child process will execute the command: ls -l after 6 seconds
total 164
-rw-rw-r-- 1 davidkebo davidkebo     32 Dec 23 18:46 README.md
-rw-rw-r-- 1 davidkebo davidkebo    874 Dec 23 18:46 expected_answer.txt
-rwxrwxr-x 1 davidkebo davidkebo 137760 Feb 22 04:12 main
-rw-rw-r-- 1 davidkebo davidkebo   2967 Dec 23 18:46 main-starter.cpp
-rw-rw-r-- 1 davidkebo davidkebo   3245 Feb 16 20:14 main.cpp
-rw-rw-r-- 1 davidkebo davidkebo    405 Feb 16 17:00 makefile
-rwxrwxr-x 1 davidkebo davidkebo   1300 Dec 23 18:46 quiz1-tests.sh
drwxrwxr-x 2 davidkebo davidkebo   4096 Dec 23 18:46 test-files

Hello from the parent process!
The child process ID is 144421
The child process exited normally
```

## Expected output for a child termination
```
Hello from the child process!
The parent process ID is 145333
The child process is exiting

Hello from the parent process!
The child process ID is 145334
The child process exited due to the kill signal
```
