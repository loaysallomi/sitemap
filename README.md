# sitemap
<pre>
<code>
Mermaid
graph TD
    Home[Home Page]
    Add[Add Task]
    Active[Active Tasks]
    Completed[Completed Tasks]
    Timer[Pomodoro Timer]

    AddForm[Submit Form]
    InsertTask[Insert Task into Database]
    Redirect[Redirect to Active Tasks]
    Checkbox[Checkbox Click]
    UpdateStatus[Update Task Status to Completed]
    Refresh[Refresh]
    Load[Load Page]
    Fetch[Fetch Completed Tasks from Database]
    StartTimer[Start Timer]
    SaveSession[Save Pomodoro Session to Database]

    Home --> Add
    Home --> Active
    Home --> Completed
    Home --> Timer

    Add --> AddForm --> InsertTask --> Redirect
    Active --> Checkbox --> UpdateStatus
    Active --> Refresh
    Completed --> Load --> Fetch
    Timer --> StartTimer --> SaveSession
</code>
</pre>
