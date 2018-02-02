# Lab2_OperatingSystems

cd <directory> - Change the current default directory to
<directory>. If the <directory> argument is not present, report
the current directory. If the directory does not exist an appropriate
error should be reported. This command should also change the PWD
environment variable.

clr - Clear the screen.

dir <directory> - List the contents of directory <directory>.

environ - List all the environment strings.

echo <comment> - Display <comment> on the display followed by a
new line (multiple spaces/tabs may be reduced to a single space).

help - Display the user manual using the more filter.

pause - Pause operation of the shell until 'Enter' is pressed.

quit - Quit the shell.

The shell environment should contain shell=<pathname>/myshell
where <pathname>/myshell is the full path for the shell executable
(not a hardwired path back to your directory, but the one from which
it was executed).
