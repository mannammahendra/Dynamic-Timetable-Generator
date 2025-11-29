# Dynamic Time Table Generator

The whole project is done using flask framework and uses python to write the main logic of the code. The templates folder will provide interactive HTML pages, which acts an interface between the user and the backend code logic.

The project takes the courses and the corresponding lecturers to teach those courses to different batches provided the break times and lunch times for each of the classess. The the appplication will process all the input and generate the possible time table. 

If there is any conflit occurs in the time table makin gprocess, like same teacher in two different classess at the same time, the the system will roll back and try to make another possible time table. After a certain tries if it still fails in making the time table, then the application will return saying that there is no possible time table for this or try again later.

Use the commands to run the project:

>  ```bash
> pip install -r requirements.txt
> python app.py
> ```

If the user wants to run this project in seperate environment, use the following commands to activate the environment before running the above commands:
> ```bash
> python3 -m venv venv
> source venv/bin/activate
> ```

