# credit-risk-management
Github commands used:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Docker:

    docker build -t <folder_name> .
    docker run <folder_name

Steps:

    Building the files required: app.py: flask code, requirements.txt: contains required libraries, credit_risk_dataset.csv: The required dataset for this model, train_model.py: code to test the file, Dockerfile: contains commands to be run in docker
    Create a new item under Freestyle Project type in Jenkins.
    Select Git in Source Code Management and paste your repository url in the given space
    Add Execute windows batch command in Build Steps
    Build now and visualize console output
    Open command prompt with the directory of the folder with the required file
    Run the docker commands mentioned above
    Visualize the output in both command prompt and Docker desktop app

Output:![my3 docker proof credit risk management](https://github.com/user-attachments/assets/97442af8-a9cd-46a6-addf-5c3861440c3c)

