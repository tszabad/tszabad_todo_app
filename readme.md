# Welcome to my Todo App!

### The app can create, read, update and delete todo list for different users.

***Basic usage:*** \
To start the todo app, type in the command line "python todo_app.py" and then the necessary arguments. If no argumnet(s) is provided, then the possible command options are printed out. The program is multiuser, so it always asks for the user id, when a new command is entered. After the commands type a space, then the second argument should be typed in.


 ***Commands:*** \
	**-la**  	Lists all the tasks \
    **-l**   	Lists all undone tasks \
    **-a**   	Adds a new task \
		            Use it with a 2nd argument in quotation marks "" to write in the task \
    **-r**   	Removes a task \
	                Use it with a 2nd argument with the number of task you want to remove \
    **-c**   	Completes a task \
	                Use it with a 2nd argument with the number of task you want to check to done. \
    **-am**     Adds multiple new tasks \
                    Use it with multiple argument each in quotation marks "" to write in the tasks \
	**-dd**     Deletes all done tasks \
	**-d**   	Deletes all tasks(danger!) \  
\
After entering the commands and argument(s) the program asks for your user id. Please enter your user id and press enter. 

***Usage example:*** \
python todo_app.py -a "new task" / new task is added to the list \
python todo_app.py -c 2 / checks the second task to completed