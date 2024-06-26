{"metadata":{"kernelspec":{"display_name":"Python 3","language":"python","name":"python3"},"language_info":{"name":"python","version":"3.10.13","mimetype":"text/x-python","codemirror_mode":{"name":"ipython","version":3},"pygments_lexer":"ipython3","nbconvert_exporter":"python","file_extension":".py"},"kaggle":{"accelerator":"none","dataSources":[{"sourceId":3136,"databundleVersionId":26502,"sourceType":"competition"}],"isInternetEnabled":false,"language":"python","sourceType":"notebook","isGpuEnabled":false}},"nbformat_minor":4,"nbformat":4,"cells":[{"cell_type":"markdown","source":"**This notebook is an exercise in the [Intro to Programming](https://www.kaggle.com/learn/intro-to-programming) course.  You can reference the tutorial at [this link](https://www.kaggle.com/alexisbcook/arithmetic-and-variables).**\n\n---\n","metadata":{}},{"cell_type":"markdown","source":"This exercise will get you started with running your own code.  \n\n# Set up the notebook\n\nTo begin, run the code in the next cell.\n- Begin by clicking inside the code cell.  \n- Click on the triangle (in the shape of a \"Play button\") that appears to the left of the code cell.\n- If your code was run sucessfully, you will see `Setup Complete` as output below the cell.\n\nInstead of clicking on the triangle, you can also run code by pressing Shift + Enter on your keyboard.  Try this now!  Nothing bad will happen if you run the code more than once.","metadata":{}},{"cell_type":"code","source":"# Set up the exercise\nfrom learntools.core import binder\nbinder.bind(globals())\nfrom learntools.intro_to_programming.ex1 import *\nprint('Setup complete.')","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:12:14.670378Z","iopub.execute_input":"2024-06-15T14:12:14.670784Z","iopub.status.idle":"2024-06-15T14:12:15.113153Z","shell.execute_reply.started":"2024-06-15T14:12:14.670752Z","shell.execute_reply":"2024-06-15T14:12:15.112036Z"},"trusted":true},"execution_count":6,"outputs":[{"name":"stdout","text":"Setup complete.\n","output_type":"stream"}]},{"cell_type":"markdown","source":"The code above sets up the notebook so that it can check your answers in this exercise.  You should never modify this code.  (Otherwise, the notebook won't be able to verify that you have successfully completed the exercise.)\n\nAfter finishing all of the questions below, you'll see the exercise marked as complete on the [course page](http://www.kaggle.com/learn/intro-to-programming).  Once you complete all of the lessons, you'll get a course completion certificate!\n\n# Question 1\n\nNext, you will run some code from the tutorial, so you can see how it works for yourself.  Run the next code cell without changes.","metadata":{}},{"cell_type":"code","source":"print(\"Hello, world!\")\n\n# DO NOT REMOVE: Mark this question as completed\nq1.check()\n","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:12:29.187992Z","iopub.execute_input":"2024-06-15T14:12:29.189107Z","iopub.status.idle":"2024-06-15T14:12:29.199719Z","shell.execute_reply.started":"2024-06-15T14:12:29.189069Z","shell.execute_reply":"2024-06-15T14:12:29.198672Z"},"trusted":true},"execution_count":7,"outputs":[{"name":"stdout","text":"Hello, world!\n","output_type":"stream"},{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"outcomeType\": 1, \"valueTowardsCompletion\": 0.2, \"interactionType\": 1, \"questionType\": 2, \"questionId\": \"1_RunHelloWorld\", \"learnToolsVersion\": \"0.3.4\", \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\"}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"If you see 'Hello, world!' above, You have successfully printed a message, and you're ready to move on to the next question.","text/markdown":"<span style=\"color:#33cc33\">If you see 'Hello, world!' above, You have successfully printed a message, and you're ready to move on to the next question.</span>"},"metadata":{}}]},{"cell_type":"markdown","source":"You just ran code to print `Hello world!`, which you should see in the output above.\n\nThe second line of code (`q1.check()`) checks your answer.  You should never modify this checking code; if you remove it, you won't get credit for completing the problem.\n\n# Question 2\n\nNow, you will print another message of your choosing.  To do this, change `print(\"Your message here!\")` to use a different message.  For instance, you might like to change it to something like:\n- `print(\"Good morning!\")`\n- `print(\"I am learning how to code :D\")`\n\nOr, you might like to see what happens if you write something like `print(\"3+4\")`.  Does it return 7, or does it just think of `\"3+4\"` as just another message?\n\nMake sure that your message is enclosed in quotation marks (`\"`), and the message itself does not use quotation marks. For instance, this will throw an error: `print(\"She said \"great job\" and gave me a high-five!\")` because the message contains quotation marks.  If you decide to take the Python course after completing this course, you will learn more about how to avoid this error in [Lesson 6](https://www.kaggle.com/colinmorris/strings-and-dictionaries).\n\nFeel free to try out multiple messages!","metadata":{}},{"cell_type":"code","source":"# TODO: Change the message\nprint(\"Your message here!\")\n\n# DO NOT REMOVE: Mark this question as completed \nq2.check()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:12:51.762476Z","iopub.execute_input":"2024-06-15T14:12:51.762844Z","iopub.status.idle":"2024-06-15T14:12:51.773218Z","shell.execute_reply.started":"2024-06-15T14:12:51.762816Z","shell.execute_reply":"2024-06-15T14:12:51.772065Z"},"trusted":true},"execution_count":9,"outputs":[{"name":"stdout","text":"Your message here!\n","output_type":"stream"},{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"outcomeType\": 1, \"valueTowardsCompletion\": 0.2, \"interactionType\": 1, \"questionType\": 2, \"questionId\": \"2_PrintAnotherMsg\", \"learnToolsVersion\": \"0.3.4\", \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\"}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Once you have printed your own message, you're ready to move on to the next question.","text/markdown":"<span style=\"color:#33cc33\">Once you have printed your own message, you're ready to move on to the next question.</span>"},"metadata":{}}]},{"cell_type":"markdown","source":"# Question 3\n\nAs you learned in the tutorial, a comment in Python has a pound sign (`#`) in front of it, which tells Python to ignore the text after it.\n\nPutting a pound sign in front of a line of code will make Python ignore that code.  For instance, this line would be ignored by Python, and nothing would appear in the output:\n```python\n#print(1+2)\n```\nRemoving the pound sign will make it so that you can run the code again. When we remove the pound sign in front of a line of code, we call this **uncommenting**.\n\nIn this problem, you will uncomment two lines in the code cell below and view the output:\n- Remove the `#` in front of `q3.hint()`.  To avoid errors, do NOT remove the `#` in front of `# Uncomment to view hint`.  \n- Next, remove the `#` in front of `q3.solution()`.\n\nAs in the previous questions, do not change the final line of code that marks your work as completed.","metadata":{}},{"cell_type":"code","source":"# Uncomment to get a hint\nq3.hint()\n\n# Uncomment to view solution\nq3.solution()\n\n# DO NOT REMOVE: Check your answer\nq3.check()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:13:58.935306Z","iopub.execute_input":"2024-06-15T14:13:58.935734Z","iopub.status.idle":"2024-06-15T14:13:58.954482Z","shell.execute_reply.started":"2024-06-15T14:13:58.935701Z","shell.execute_reply":"2024-06-15T14:13:58.953006Z"},"trusted":true},"execution_count":10,"outputs":[{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"interactionType\": 2, \"questionType\": 2, \"questionId\": \"3_LearnCheckingCode\", \"learnToolsVersion\": \"0.3.4\", \"valueTowardsCompletion\": 0.0, \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\", \"outcomeType\": 4}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Hint: If you're ever stuck on a question, it's a good idea to look at the hint before viewing the solution.","text/markdown":"<span style=\"color:#3366cc\">Hint:</span> If you're ever stuck on a question, it's a good idea to look at the hint before viewing the solution."},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"interactionType\": 3, \"questionType\": 2, \"questionId\": \"3_LearnCheckingCode\", \"learnToolsVersion\": \"0.3.4\", \"valueTowardsCompletion\": 0.0, \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\", \"outcomeType\": 4}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Solution: If you're still stuck on a question after viewing the hint and re-reading the tutorial, you can view the solution.  You can also view the solution after you have successfully submitted your own answer, to check if the official solution is any different (there may be more than one right answer!).","text/markdown":"<span style=\"color:#33cc99\">Solution:</span> If you're still stuck on a question after viewing the hint and re-reading the tutorial, you can view the solution.  You can also view the solution after you have successfully submitted your own answer, to check if the official solution is any different (there may be more than one right answer!)."},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"outcomeType\": 1, \"valueTowardsCompletion\": 0.2, \"interactionType\": 1, \"questionType\": 2, \"questionId\": \"3_LearnCheckingCode\", \"learnToolsVersion\": \"0.3.4\", \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\"}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Once you have printed the hint and the solution, you're ready to move on to the next question.","text/markdown":"<span style=\"color:#33cc33\">Once you have printed the hint and the solution, you're ready to move on to the next question.</span>"},"metadata":{}}]},{"cell_type":"markdown","source":"In the next question, and in most of the exercises in this course, you will have the option to uncomment to view hints and solutions.  Once you feel comfortable with uncommenting, continue to the next question.\n","metadata":{}},{"cell_type":"markdown","source":"# Question 4\n\nIn the tutorial, you defined several variables to calculate the total number of seconds in a year.  Run the next code cell to do the calculation here.","metadata":{}},{"cell_type":"code","source":"# Create variables\nnum_years = 4\ndays_per_year = 365 \nhours_per_day = 24\nmins_per_hour = 60\nsecs_per_min = 60\n\n# Calculate number of seconds in four years\ntotal_secs = secs_per_min * mins_per_hour * hours_per_day * days_per_year * num_years\nprint(total_secs)","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:14:09.930629Z","iopub.execute_input":"2024-06-15T14:14:09.931035Z","iopub.status.idle":"2024-06-15T14:14:09.940923Z","shell.execute_reply.started":"2024-06-15T14:14:09.930987Z","shell.execute_reply":"2024-06-15T14:14:09.939073Z"},"trusted":true},"execution_count":11,"outputs":[{"name":"stdout","text":"126144000\n","output_type":"stream"}]},{"cell_type":"markdown","source":"Use the next code cell to:\n- Define a variable `births_per_min` and set it to 250.  (There are on average 250 babies born each minute.)\n- Define a variable `births_per_day` that contains the average number of babies born each day.  (To set the value of this variable, you should use `births_per_min` and some of the variables from the previous code cell.)\n\nRemember you can always get a hint if you need it!","metadata":{}},{"cell_type":"code","source":"# TODO: Set the value of the births_per_min variable\nbirths_per_min = 250\n\n# TODO: Set the value of the births_per_day variable\nbirths_per_day = births_per_min*1440\n\n# DO NOT REMOVE: Check your answer\nq4.check()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:19:00.980649Z","iopub.execute_input":"2024-06-15T14:19:00.981008Z","iopub.status.idle":"2024-06-15T14:19:00.989755Z","shell.execute_reply.started":"2024-06-15T14:19:00.980980Z","shell.execute_reply":"2024-06-15T14:19:00.988727Z"},"trusted":true},"execution_count":15,"outputs":[{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"outcomeType\": 1, \"valueTowardsCompletion\": 0.2, \"interactionType\": 1, \"questionType\": 1, \"questionId\": \"4_BirthsPerYear\", \"learnToolsVersion\": \"0.3.4\", \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\"}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Correct","text/markdown":"<span style=\"color:#33cc33\">Correct</span>"},"metadata":{}}]},{"cell_type":"code","source":"# Uncomment to get a hint\n#q4.hint()\n\n# Uncomment to view solution\n#q4.solution()","metadata":{},"execution_count":null,"outputs":[]},{"cell_type":"markdown","source":"# 🌶️ Question 5\n\n(Questions marked with a 🌶️ will be a little bit more challenging than the others!  Remember you can always get a hint or view the solution.)\n\nThe [Titanic competition](https://www.kaggle.com/c/titanic) is Kaggle's most famous data science competition. In this competition, participants are challenged to build a machine learning model that can predict whether or not passengers survived the Titanic shipwreck, based on information like age, sex, family size, and ticket number.\n\nRun the next code cell without changes to load and preview the titanic data.\n\nDon't worry about the details of the code for now - the end result is just that the all of the titanic data has been loaded in a variable named `titanic_data`.  (In order to learn how to write this code yourself, you can take the [Python course](https://www.kaggle.com/learn/python) and then the [Pandas course](https://www.kaggle.com/learn/pandas).)","metadata":{}},{"cell_type":"code","source":"# Load the data from the titanic competition\nimport pandas as pd\ntitanic_data = pd.read_csv(\"../input/titanic/train.csv\")\n\n# Show the first five rows of the data\ntitanic_data.head()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:20:16.619414Z","iopub.execute_input":"2024-06-15T14:20:16.619778Z","iopub.status.idle":"2024-06-15T14:20:16.689053Z","shell.execute_reply.started":"2024-06-15T14:20:16.619744Z","shell.execute_reply":"2024-06-15T14:20:16.687967Z"},"trusted":true},"execution_count":16,"outputs":[{"execution_count":16,"output_type":"execute_result","data":{"text/plain":"   PassengerId  Survived  Pclass  \\\n0            1         0       3   \n1            2         1       1   \n2            3         1       3   \n3            4         1       1   \n4            5         0       3   \n\n                                                Name     Sex   Age  SibSp  \\\n0                            Braund, Mr. Owen Harris    male  22.0      1   \n1  Cumings, Mrs. John Bradley (Florence Briggs Th...  female  38.0      1   \n2                             Heikkinen, Miss. Laina  female  26.0      0   \n3       Futrelle, Mrs. Jacques Heath (Lily May Peel)  female  35.0      1   \n4                           Allen, Mr. William Henry    male  35.0      0   \n\n   Parch            Ticket     Fare Cabin Embarked  \n0      0         A/5 21171   7.2500   NaN        S  \n1      0          PC 17599  71.2833   C85        C  \n2      0  STON/O2. 3101282   7.9250   NaN        S  \n3      0            113803  53.1000  C123        S  \n4      0            373450   8.0500   NaN        S  ","text/html":"<div>\n<style scoped>\n    .dataframe tbody tr th:only-of-type {\n        vertical-align: middle;\n    }\n\n    .dataframe tbody tr th {\n        vertical-align: top;\n    }\n\n    .dataframe thead th {\n        text-align: right;\n    }\n</style>\n<table border=\"1\" class=\"dataframe\">\n  <thead>\n    <tr style=\"text-align: right;\">\n      <th></th>\n      <th>PassengerId</th>\n      <th>Survived</th>\n      <th>Pclass</th>\n      <th>Name</th>\n      <th>Sex</th>\n      <th>Age</th>\n      <th>SibSp</th>\n      <th>Parch</th>\n      <th>Ticket</th>\n      <th>Fare</th>\n      <th>Cabin</th>\n      <th>Embarked</th>\n    </tr>\n  </thead>\n  <tbody>\n    <tr>\n      <th>0</th>\n      <td>1</td>\n      <td>0</td>\n      <td>3</td>\n      <td>Braund, Mr. Owen Harris</td>\n      <td>male</td>\n      <td>22.0</td>\n      <td>1</td>\n      <td>0</td>\n      <td>A/5 21171</td>\n      <td>7.2500</td>\n      <td>NaN</td>\n      <td>S</td>\n    </tr>\n    <tr>\n      <th>1</th>\n      <td>2</td>\n      <td>1</td>\n      <td>1</td>\n      <td>Cumings, Mrs. John Bradley (Florence Briggs Th...</td>\n      <td>female</td>\n      <td>38.0</td>\n      <td>1</td>\n      <td>0</td>\n      <td>PC 17599</td>\n      <td>71.2833</td>\n      <td>C85</td>\n      <td>C</td>\n    </tr>\n    <tr>\n      <th>2</th>\n      <td>3</td>\n      <td>1</td>\n      <td>3</td>\n      <td>Heikkinen, Miss. Laina</td>\n      <td>female</td>\n      <td>26.0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>STON/O2. 3101282</td>\n      <td>7.9250</td>\n      <td>NaN</td>\n      <td>S</td>\n    </tr>\n    <tr>\n      <th>3</th>\n      <td>4</td>\n      <td>1</td>\n      <td>1</td>\n      <td>Futrelle, Mrs. Jacques Heath (Lily May Peel)</td>\n      <td>female</td>\n      <td>35.0</td>\n      <td>1</td>\n      <td>0</td>\n      <td>113803</td>\n      <td>53.1000</td>\n      <td>C123</td>\n      <td>S</td>\n    </tr>\n    <tr>\n      <th>4</th>\n      <td>5</td>\n      <td>0</td>\n      <td>3</td>\n      <td>Allen, Mr. William Henry</td>\n      <td>male</td>\n      <td>35.0</td>\n      <td>0</td>\n      <td>0</td>\n      <td>373450</td>\n      <td>8.0500</td>\n      <td>NaN</td>\n      <td>S</td>\n    </tr>\n  </tbody>\n</table>\n</div>"},"metadata":{}}]},{"cell_type":"markdown","source":"The data has a different row for each passenger.  \n\nThe next code cell defines and prints the values of three variables:  \n- `total` = total number of passengers who boarded the ship\n- `survived` = number of passengers who survived the shipwreck\n- `minors` = number of passengers under 18 years of age\n\nRun the code cell without changes.  (Don't worry about the details of how these variables are calculated for now.  You can learn more about how to calculate these values in the [Pandas course](https://www.kaggle.com/learn/pandas).)","metadata":{}},{"cell_type":"code","source":"# Number of total passengers\ntotal = len(titanic_data)\nprint(total)\n\n# Number of passengers who survived\nsurvived = (titanic_data.Survived == 1).sum()\nprint(survived)\n\n# Number of passengers under 18\nminors = (titanic_data.Age < 18).sum()\nprint(minors)","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:20:45.730960Z","iopub.execute_input":"2024-06-15T14:20:45.731353Z","iopub.status.idle":"2024-06-15T14:20:45.739508Z","shell.execute_reply.started":"2024-06-15T14:20:45.731322Z","shell.execute_reply":"2024-06-15T14:20:45.738409Z"},"trusted":true},"execution_count":17,"outputs":[{"name":"stdout","text":"891\n342\n113\n","output_type":"stream"}]},{"cell_type":"markdown","source":"So, \n- `total = 891` (there were 891 passengers on board the Titanic),\n- `survived = 342` (342 passengers survived), and \n- `minors = 113` (113 passengers were under the age of 18).\n\nIn the code cell below, replace the underlines (`____`) with code to calculate the values for two more variables:\n- `survived_fraction` should be set to the fraction of passengers who survived the Titanic disaster.\n- `minors_fraction` should be the fraction of passengers who were minors (under the age of 18).\n\nFor each variable, your answer should be a number between 0 and 1.  \n\nIf you need a hint or want to view the solution, you can skip to the next code cell and uncomment the appropriate lines of code (`q5.hint()` and `q5.solution()`).","metadata":{}},{"cell_type":"code","source":"# TODO: Fill in the value of the survived_fraction variable\nsurvived_fraction = 342/891\n\n# Print the value of the variable\nprint(survived_fraction)\n\n# TODO: Fill in the value of the minors_fraction variable\nminors_fraction = 113/891\n\n# Print the value of the variable\nprint(minors_fraction)\n\n# DO NOT REMOVE: Check your answer\nq5.check()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:22:48.115457Z","iopub.execute_input":"2024-06-15T14:22:48.115843Z","iopub.status.idle":"2024-06-15T14:22:48.125965Z","shell.execute_reply.started":"2024-06-15T14:22:48.115810Z","shell.execute_reply":"2024-06-15T14:22:48.124705Z"},"trusted":true},"execution_count":18,"outputs":[{"name":"stdout","text":"0.3838383838383838\n0.12682379349046016\n","output_type":"stream"},{"output_type":"display_data","data":{"text/plain":"<IPython.core.display.Javascript object>","application/javascript":"parent.postMessage({\"jupyterEvent\": \"custom.exercise_interaction\", \"data\": {\"outcomeType\": 1, \"valueTowardsCompletion\": 0.2, \"interactionType\": 1, \"questionType\": 1, \"questionId\": \"5_BonusTitanic\", \"learnToolsVersion\": \"0.3.4\", \"failureMessage\": \"\", \"exceptionClass\": \"\", \"trace\": \"\"}}, \"*\")"},"metadata":{}},{"output_type":"display_data","data":{"text/plain":"Correct","text/markdown":"<span style=\"color:#33cc33\">Correct</span>"},"metadata":{}}]},{"cell_type":"code","source":"# Uncomment to receive a hint\n#q5.hint()\n\n# Uncomment to view the solution\n#q5.solution()","metadata":{"execution":{"iopub.status.busy":"2024-06-15T14:22:53.133769Z","iopub.execute_input":"2024-06-15T14:22:53.134170Z","iopub.status.idle":"2024-06-15T14:22:53.138592Z","shell.execute_reply.started":"2024-06-15T14:22:53.134139Z","shell.execute_reply":"2024-06-15T14:22:53.137498Z"},"trusted":true},"execution_count":19,"outputs":[]},{"cell_type":"markdown","source":"# Bonus Exercise\n\nAs an **optional** next step, you're encouraged to make a submission to the Titanic competition.  \n> To do this, follow the instructions in the **[notebook here](https://www.kaggle.com/alexisbcook/titanic-tutorial)**.  \n\nThe notebook is beginner-friendly and does not assume you have any experience with coding.  At the same time, you'll learn how to author your own notebooks on Kaggle, and it gives you a great idea of what you'll be able to do if you continue to learn data science!\n\n# Keep going\n\nCongratulations!  You have just finished the first exercise in the Intro to Programming course!  \n\nYou are now ready to learn how to **[organize your code with functions](https://www.kaggle.com/alexisbcook/functions)**.","metadata":{}},{"cell_type":"markdown","source":"---\n\n\n\n\n*Have questions or comments? Visit the [course discussion forum](https://www.kaggle.com/learn/intro-to-programming/discussion) to chat with other learners.*","metadata":{}}]}