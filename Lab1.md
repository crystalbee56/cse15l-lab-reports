# Using the "cs" command.

## 1. With no arguments.
- If you type cd with no arguments, it will keep you in the current directory of the workspace.
- <img width="135" alt="image" src="https://github.com/crystalbee56/cse15l-lab-reports/assets/146876074/f5c169ce-20c0-47fe-a64e-cbd71ff3b36f">
- The command was run in "/home" directory.
- Running this command didn't produce  any output because it's a command to change the working directory, not to display information. It simply updates your current
  directory to the same location you were in before.
- There wasn't any error because there was no output to begin with.

## 2. With a path to a directory as an argument.
- Let's say you have a directory called "documents" inside the workspace. You can use the command "cd documents" to navigate to that directory.
- <img width="180" alt="image" src="https://github.com/crystalbee56/cse15l-lab-reports/assets/146876074/c7654db5-889a-4dec-8d26-e4c8f98f8579">
- The current directory is the "/home" directory.
- The directory was simply changed to "lecture1" without any output.
- There were no error messages. However, if the directory does not exist or you don't have the required permissions, you may receive an error message indicating that the
  directory could not be found or accessed.

## 3. with a path to a file as an argument
- The "cd" command doesn't work with file paths. It can only be used to change directories.
- <img width="259" alt="image" src="https://github.com/crystalbee56/cse15l-lab-reports/assets/146876074/167aeb76-6691-425e-901d-57def0607f7b">
- It was in the "lecture1" directory.
- The output of this was a message indicating that "Hello.java" is not a directory. This is because the "cd" command can only be used for directories.
- No error


# Using the "ls" command

## 1. With no arguments.
- let's say the working directory was "/home/lecture1" when the "ls" command was run with no arguments.
- <img width="266" alt="image" src="https://github.com/crystalbee56/cse15l-lab-reports/assets/146876074/c9a07234-5455-497d-8a58-d9a796584cc0">
- In this case, the output would be a list of files and directories present in the current working directory ("/home/lecture1"). 
- After running this command in the directory "/home", it showed the lists of files in that directory."Having no arguments with the "ls" command means
  that it will list the contents of the current directory by default. The output would show the names of files and directories in the current working directory. 
- This is not an error. It's a normal behavior of the "ls" command to list the contents of the current directory when no arguments are provided.


## 2. With a path to a directory as an argument.
- Let's say the working directory was "/home/user" when the "ls" command was run with a path to a directory, let's say "/home/user/documents".
- <img width="248" alt="image" src="https://github.com/crystalbee56/cse15l-lab-reports/assets/146876074/3ec13be1-0936-4cfe-a73e-caa53a7cad65">

- The directory before this was run is the "lecture1" directory.
- In this case, the output of the "ls" command would be a list of files and directories present in the specified directory ("/home/user/documents"). The output would show the
  names of files and directories within that specific directory.
- This is not an error. It's the expected behavior of the "ls" command when provided with a path to a directory. It will list the contents of the specified directory.


## 3. with a path to a file as an argument.
- Let's say the working directory was "/home/lecture1" when the "ls" command was run with a path to a file as an argument, let's say "/home/lecture1/messages/language-code.txt".
- 
- The directory before this was run is the "lecture1" directory.
- In this case, the output of the "ls" command would be the name of the specified file, "example.txt". 
- Since the "ls" command is used to list files and directories, providing a path to a file as an argument will simply display the name of that file. It's not an error, but rather
- a way to confirm the existence of the file in the specified location.
