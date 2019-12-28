
# A Todo App

    
A simple todo-application with certain features listed in the following sections. 


A todo-application helps you to keep track of your tasks that you want to complete on any given day/time.

Components on the page

1.  Task button: A composer button, which we usually see at the bottom right corner of any application. The text of the button is a plus symbol (+).
    
2.  Adding a task : Clicking on the + button opens a modal.

3.  Action buttons of the form: Like all modals, this will have two buttons: i) Save Task, ii) Cancel
    
4.  Actions:
    1. Save Task: When a user clicks on save button, the UI indicates that the API call is in progress.
    2. Cancel: All the changes done by the user in the form are discarded.

5.  Tabs: The page contains 3 tabs
	1. All tasks: this tab will contain all the tasks.
	2. Completed: this tab will contain only completed tasks.
	3. Pending: this tab will contain only pending tasks.

6. List view of the tasks: The content of each tab will be a list of tasks with following columns

`Summary | Priority | Created On | Due Date | Actions`


7.  Actions: Icons for edit, delete, and close/open the task.
    
9.  Group By dropdown: A dropdown to allow the current tab’s list to be grouped by selected item.

1.  ### How to add a task?
    

To add a task, click on the + button present at the bottom-right corner of the application. A modal will open with add-task-form.

2.  ### What happens when a user adds a task?
    

By default the task is treated as an open task. This task is added at the top of the list in both “All tasks” and “Pending” tasks tabs.
    

To edit a task, click on the edit icon available in the Actions column of a row. When a user clicks on the edit icon, a modal will open with add-task-form. The values of the current task will be prefilled in the form.

Note: Unlike add, on editing the position of the task in the list should not change.

4.  ### How to delete a task?
    

To delete a task, click on the delete icon available in the Actions column of a row. When a user clicks on the delete icon, a modal will open with the task summary.

5.  ### How to mark a task as completed?

Click the done button available in the Actions column.

6.  ### When a user marks a task as done?
	1. In the all tasks lists, the style of the task changes the background to green
	2. The “done” button changes to “re-open” in the actions column.
	3. A copy of task is be moved to “Completed” tab.

7.  ### Task as pending:

Click the re-open button available in the Actions column.

8.  when a user reopens a task: 
    
	1. In all tasks list, the style of tasks become normal.
	2. The “re-open” button should changes to “done” button.
	3. The task from “Completed” tab is moved to “Pending”.
 
    







  
