# worldcup-database
This is one of the required projects to earn your certification. For this project, you will create a Bash script that enters information from World Cup games into PostgreSQL, then query the database for useful statistics.

This course runs in a virtual Linux machine on your computer. To run the course, you first need to download each of the following if you don't already have them:

Docker Engine
VS Code and the Dev Containers extension
Git
Then, follow these instructions to start the course:

Open a terminal and clone the RDB Alpha repo if you don't already have it with git clone https://github.com/freeCodeCamp/rdb-alpha
Navigate to the rdb-alpha directory in the terminal with cd rdb-alpha, and open VS Code with code .
If you want to save your progress to your freeCodeCamp account, do the following:

Generate a user token if you don't already have one:
Generate User Token
Copy your user token:
Copy User Token
In the VS Code that opened, find and open the file named Dockerfile. At the bottom of the file, paste your token in as the value for the CODEROAD_WEBHOOK_TOKEN variable. It should look like this: ENV CODEROAD_WEBHOOK_TOKEN=your-token-here
If you log out of freeCodeCamp before you complete the entire Build a World Cup Database course, your user token will be deleted and your progress will not be saved to your freeCodeCamp account.
Open the command palette in VS Code by expanding the "View" menu and clicking "Command Palette..." and enter Dev Containers: Rebuild and Reopen in Container in the input.
A new VS Code window will open and begin building the Docker image. It will take several minutes the first time.
Once it is finished building, open the command palette again and enter CodeRoad: Start to open CodeRoad.
In the CodeRoad window, click "Start New Tutorial" and then the "URL" tab at the top.
Copy the course URL below, paste it in the URL input, and click "Load".
Copy Course URL
Click "Start" to begin.
Follow the instructions in CodeRoad to complete the course. Note: You may need to restart the terminal once for terminal settings to take effect and the tests to pass.
Complete both steps below to finish the challenge.
Step 1: Complete the project
The project runs in a virtual machine, complete the user stories described in there and get all the tests to pass to finish step 1.
Important: After you pass all the project tests, save a dump of your database into a worldcup.sql file, as well as your insert_data.sh and queries.sh files, so you can complete step 2. There will be instructions how to do that within the virtual machine.

Step 2: Submit your code
When you have completed the project, save all the required files into a public repository and submit the URL to it below.
Required files: worldcup.sql, insert_data.sh, queries.sh

