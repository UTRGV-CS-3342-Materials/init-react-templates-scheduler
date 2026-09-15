# FEATURES

Update with every commit. Put a status (in-progress) or (complete) at the end of each line that you work on.

# Step 1: Setup
* 1.1 Start a node/express server on localhost
* 1.2 Serve the / route
* 1.3 Use a react component to generate HTML for that route

# Step 2: Database
* 2.1 Create a new database
* 2.2 Create a course table with id (primary key, autoincrement)
* 2.3 Create an instructor table with name and id
* 2.4 Create a section table that links to course (course_id) and instructor (instructor_id)
* 2.5 Show some piece of db data on the 1.3 test page

# Step 3: View
* 3.1 Display the mockup html page using Layout and Page components
* 3.2 Display each course with a Course component
* 3.3 Dynamically generate instructor select boxes from the instructor data
* 3.4 Display each section with a Section component

# Step 4: Add Course
* 4.1 POST new course number to POST route
* 4.2 save new course in db and redirect

# Step 5: Update All
* 5.1 POST update all with select box values to POST route
* 5.2 update instructors in db
* 5.3 add new sections in db and redirect
