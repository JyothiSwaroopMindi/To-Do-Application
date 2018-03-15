Creating A To-Do Application
 
 1.Download and install Node from nodejs.org,
 2.Then install React in your system using Node through cmd,
 3.create a folder in which the To-Do Application should be present,
 4.In that folder add package.json.package-lock.json add public,src folders  in public include bundle.js and index.html
 5.in src add app.js,index.css,index.js and a new folder named components 
 6.in components add create-todo.css,create-todo.js,todos-list-header.js,todos-list-item.css,todos-list-item.js,todos-list.js
 7.Switch to that folder in cmd  type the command npm start,
 8.It opens u a localhost in your browser and displays the required To-Do Application,


 
  Description:
    In this To-Do Application, there is a demo with two tasks added 
   => The one which is red colour says an incomplete task,
   => The one which is green colour says a completed task,
 
   We can ADD tasks by clikcing on Add
   We can MODIFY tasks by clikcing on Modify
   We can DELETE tasks by clikcing on Delete
   For COMPLETION of task : If The task is completed simply click on it and that turns to green which means the task is completed
                               Initial Addition of task is incomplete hence it is in red colour                           
   For LOGICAL VALIDATION: If you add an empty task without typing, it says "Please enter a task."
                           If you add task which is already existing, it says "Task already exists."  
   