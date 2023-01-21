# TodoList-Using-Local-Storage
Todo List Using Local Storage
Make the following ui - Figma Link- https://www.figma.com/file/ILbMUKhGSq9Ha8naSgztXr/Untitled?node-id=0%3A1&t=voDxagreIkN7YnJp-1

Task is to make a todo list application managed using localstorage. 
Make 4 sections
i. First one to add the item. Every item should contain an item name, item date (deadline) and priority. The priority input is a select dropdown which can be high, medium or low.
ii. Second section is Today's Tasks - this is where all the tasks which have the deadline of the current date (or today) will be shown.
iii. The third section is the future tasks - where the tasks of the future dates will be shown, or the tasks which havent been completed will be shown. Show the tasks which haven't be completed and the date has passed with a red border instead of a black one.
iv. The fourth section is the completed Tasks - All of the tasks which have been completed are shown here.

Functionality
i. The add item button adds an item ( the entire object) in the todolist array which is maintained using local storage.
ii. The delete button shown in the todo list item card is just to delete the item from the array
iii. the tick button shown in the todo list item is to mark the item as completed or not completed.
Hint: Your todo list array in localstorage should look like - [{name:"", date:"", priority:"", completed:false}]
