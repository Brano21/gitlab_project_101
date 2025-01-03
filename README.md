# Test Repository

This repository was created to experiment with GitHub and explore its basic functionality.

## Steps

1. **Set up the GitHub repository**:  
   Configure the basic settings, such as the repository name, visibility (private/public), etc.

2. **Add an SSH key**:  
   Generate an SSH key and link it to your GitHub account:  
   ```bash
   ssh-keygen -t rsa -b 4096 -C "<email>@gmail.com"

3. **Configure git terminal**:
   Set up your Git username and email in the terminal:
   ```bash
    git config --global user.name <username> 
    git config --global user.email <email>

5. **Clone this project**:
   Clone this project to your local machine:
   ```bash
    git clone git@github.com:Brano21/test.git

7. **Create new branches, add files and push them to GitHub**:
   Create a new branch, add files, and push them to GitHub:
   ```bash
   git checkout -b <new_branch_name> 
    git add. 
    git commit -m "<commit>" 
    git push -u origin <new_branch_name> 

6. **In GitHub we Create Pull Request and then Merge Pull Request**: \
   In GitHub, create a pull request for your branch. \
   Review the changes and merge the pull request into the main branch.
