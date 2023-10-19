# Hello, world!

# cd

![Image](1.1.png)

__1. If I don't make any arguments, the cd command will print nothing. (However, if you have the cd to a new path, a separate cd will return to the /home path.)__

![Image](1.2.png)

__2. If I give the cd command a path to a directory, it will move the default working directory to that directory.__

![Image](1.3.png)

__3. If you use cd to go to a file, it will run an error and say Not a directory__

# ls

![Image](2.1png)

![Image](2.2png)

__1.Because the default path is /home, ls by itself will display the name of the first and only directory, which is lecture1. When we change the working directory to lecture1 ls with argument, it will read the names of all the files in that folder__

![Image](2.3png)

__2. When we give ls any correct directory path, it will print the name of the entire directory and the files in it. At the same time, you can notice that it marks the directory in blue.__

![Image](2.1png)

__3. When we give it a path to a file, it will run an error, display the path we gave it, and not display the class content in the file.__

# cat

![Image](3.1png)

__1. When we use a cat alone, it will enter an extraordinary state. It will not continue to pop up [user@sahara ~] to let us enter instructions but will continue to copy the content we enter until we give it an EOF signal.__

![Image](3.2png)

__2. When we give the cat a directory path, it will report an error saying that the path given to it is a directory. So, this command only allows file type arguments.__

![Image](3.3png)

__3. When the path we give it is a file, it will run normally and print the class content it can get in the file.__
