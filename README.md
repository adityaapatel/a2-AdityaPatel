Assignment 2 - Short Stack: Basic Two-tier Web Application using HTML/CSS/JS and Node.js  
===
Aditya Patel

## Bucket Buddy
A two-page web application that helps users create and manage their bucket list items. On the Home page, users can add new items by filling out a form with fields such as title, category, priority, and an optional target date. On the All Items page, users can view all items stored on the server, see derived information (like days left until their target date), and either mark them as completed or delete them.

## Technical Achievements

**Tech Achievement 1**: 
Two-page app with server-backed data
The app includes index.html (form entry) and results.html (results display).
When an item is submitted, the server updates its dataset and recalculates derived fields before sending the updated data back. The results page dynamically fetches the latest dataset and populates the table.

**Tech Achievement 2**: Full create/read/update/delete (CRUD) workflow
Create: Users can add new bucket list items via the form.
Read: The results page displays all items in a table pulled directly from the server.
Update: Users can mark an item as completed. Completed items move into a separate completed section.
Delete/Completed: Users can delete an item entirely from the server.

**Tech Achievement 3**: Derived field calculation
The server automatically calculates a daysLeft field whenever a new item is added.
This field is computed based on the targetDate minus the current date, giving users real-time tracking of how much time is left for their goal.

### Design/Evaluation Achievements
- **Design Achievement 1**: Peer Review with Aishwarya Silam
Study Design: I asked Silam to test the app by completing three tasks:
*Instructions:*
Add a new bucket list item, Mark an item as completed, Delete a completed item.

**Feedback:**
The app worked as expected for all tasks.
The main suggestion was to improve the navbar styling to make it more visually distinct and easier to notice.
*Future Changes:*
I plan to improve the navbar’s visibility by making it bolder and more visually separated from the page content.

**Live Link:**
https://a2-adityapatel-9q7y.onrender.com

**Instructions**
Go to the Home page
Fill out the form with a title, category, priority, and optional target date.
Submit the form to add your item.
Navigate to the All Items page to see the current dataset.
Use the action buttons to mark items completed or delete them.