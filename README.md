# Challenge_VC
This is my first challenge for Version Control. 

# Description
These are the step-by-step instructions for a basic lesson learned through WGU and LinkedInLearning to create a remote repository, clone it locally and adding a file to eventually push up to the remote repository on GitHub. 

## Challenge Steps 

1. Create a remote repository and initialize it with a README. 

- This is done directly on GitHub. You create a new repository, give it a name, and then check the box to add a README, then click create. 

2. Clone the remote repository to your local environment. 

- To clone to your local environment, start by opening up your device's terminal. Cd into the folder you want to clone the remote repository in. If you need to create a new folder for the remote repository to exist, the command is "mkdir folder_name". Locate your remote repository's URL on GitHub and copy it. Then, from the terminal, use the command "git clone remote_repo_URL" where you replace "remote_repo_URL" with the copied URL. By now, your remote repository should be cloned onto you local device. 

3. Add file "firstpush.txt" (add to staging area and commit locally). 

- From the terminal, you can open up the repository with visual studio code with the "code ." command. Once Visual Studio Code opens, add a file titled "firstpush.txt". Then, open up a terminal through Visual Studio Code. You can use two different commands depending on what you want to add. "git add file_name", file_name in this case being "firstpush.txt" or "git add .". Next, commit your changes with "git commit -m "Commit message". The commit message in this case could be "initial commit" or "Added firstpush.txt". Att this point you have added to the changes to the staging area and committed the changes locally. 

4. Push file to remote repository. 

- This last step is easy, from the terminal in Visual Studio Code type "git push", then check your remote repository on GitHub. Refresh and make sure you see that the file has been added. 


