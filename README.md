# quiz_app
This is a basic Quiz application, the objective of the app is to check the user's basic knowledge of Flutter.

The questions are stored inside the data model folder.

this is how the code logic works::

The app starts on Quiz_app.dart -> this is the common screen which will be updated throughout the app
Start_screen-> This is the first screen on the app,
Questions_screen -> This screen displays questions and their answers.
result_screen-> This screen displays the final result. for doing so the screen is redirected to the Questions_summery class for getting the list of questions and answers.
questions_summery -> This screen displays the questions that the user solved with the correct answers and the answers given by the users. It redirects to summeryItems screen
questions. dart -> This is a data model that stores some dummy questions.
result_identifier -> This identifies if the question was answered correctly and updates the color for the questions.
