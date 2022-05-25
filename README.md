# TurtleShell
This is a simple shell around a few of the commands in the turtle module.  

Basic turtle commands such as forward() are added to a Cmd subclass with method named do_forward(). 

The argument is converted to a number and dispatched to the turtle module. 

The docstring is used in the help utility provided by the shell.  

The shell also includes a basic record and playback facility implemented with the precmd() method which is responsible for converting the input to lowercase and writing the commands to a file. 

The do_playback() method reads the file and adds the recorded commands to the cmdqueue for immediate playback.
