# quiz1.2
Quiz 1.2: Fork + Exec
Instructions:
1. Create a child process using fork().
2. The child process should execute the command: ls -l.
3. The child process should print the parent process ID (PID).
4. The parent process should print the child process ID (PID).
5. The parent process should wait for the child process to finish.
6. The parent process should print the exit status of the child process: either WIFEXITED or WIFSIGNALED.

Hints:
1. You can use the man page for waitpid to understand the parameters.
2. The termination of a process may be due to a voluntary exit or
   due to the receipt of an unhandled signal whose default
   disposition is to terminate the process.
3. To distinguish between the two exit statuses:
   - WIFEXITED returns true if the process terminated normally.
   - WIFSIGNALED returns true if the process terminated due to the kill signal.

Usage:
./main -n <number>
