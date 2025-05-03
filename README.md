# Task-Manager
Final
hello world

Work contributed/Time:
Henry Nirajan Prject Hours: 2 hours 7 - 9 pm  _ Created Action Interface and RemoveTaskAction Implements Action


To-Do-List: Nirajan - TaskManager Class, Henry - TaskMaster Class

TaskManager Class
 (List, Stack, Queue, PriorityQueue, Map, TreeMap)

Relationships: Uses Task and Action

Fields:

private List<Task> allTasks: Stores all tasks (uses ArrayList)
private Stack<Action> undoStack: Tracks undoable actions
private Queue<Task> workQueue: Manages tasks in FIFO order (uses LinkedList)
private PriorityQueue<Task> priorityQueue: Orders tasks by priority
private Map<String, List<Task>> tasksByStatus: Groups tasks by status (uses HashMap)
private TreeMap<LocalDate, List<Task>> tasksByDueDate: Organizes tasks by due date (uses TreeMap for Binary Search Tree)

Constructors: None 

Methods:

public void addTask(Task task, boolean recordAction): Adds a task to all data structures; optionally records the action for undo.
public void removeTask(Task task, boolean recordAction): Removes a task from all data structures; optionally records the action for undo.
public void undo(): Undoes the last action by popping from undoStack.


Getters:
public Queue<Task> getWorkQueue(): Returns the work queue.
public PriorityQueue<Task> getPriorityQueue(): Returns the priority queue.
public Map<String, List<Task>> getTasksByStatus(): Returns the status map.
public TreeMap<LocalDate, List<Task>> getTasksByDueDate(): Returns the due date TreeMap.

