====================   Source Files    =======================

The following source files are not included in the original source files of
xv6 repository. They aim to aid the developers in testing the functionality
of the system calls created.

hello.c
        Source file used for testing the helloworld syscall

enablecount.c
        Source file used for testing the enablecount syscall

disablecount.c
        Source file used for testing the disablecount syscall

resetcount.c
        Source file used for testing the resetcount syscall

scarlet.c
        Source file used for testing the scarlet syscall. It accepts two
        inputs in the command line. The first input being the a PID of a
        process and the second input being the number scheduler runs by
        which the process gets skipped by the scheduler.

forky.c
        Source file used for creating a long-running process.
        The information about the long-running process are observed through
        ps commands to test the functionality of enablecount, disablecount,
        resetcount, and scarlet system call.
