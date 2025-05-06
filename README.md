# Task-Manager
Final
hello world

Work contributed/Time:
Henry and Nirajan Project Hours:5/3  2 hours 7 - 9 pm  _ Created Action Interface and RemoveTaskAction Implements Action
Henry and Nirajan Project Hours: 5/5 2 hours 7 - 9pm _ Created TaskManager class andTaskMaster class.


To-Do-List: Nirajan - AddTaskAction Class, Henry - TaskMaster Class

AddTaskAction Class
Purpose: Represents an action to undo the addition of a task.

Relationships: Implements Action.

Fields:

private Task task: The task that was added.
Constructors:

public AddTaskAction(Task task): Initializes with the task to be undone.
Methods:

public void undo(TaskManager manager): Removes the task from the manager to undo the addition.
