# coup-api
The Spring Boot API for Coup Finance.

### Development Practices
1. Create a new branch for any development
    - Branch name format `changing-some-thing`
    - Command: `git checkout -b <branchname>` 
2. Add changes to new branch
    - Try to keep additions under 300 lines
    - Try to keep the number of files under 20
3. Add the files and changes to your commit
    - `git add .`
        - For adding all changes
    - `git add <filename>` 
        - For adding a specific file
4. Commit your changes 
    - `git commit -m "<message>"`
        - Make your message a present decription of the changes
        - Ex `"Adding try catch to validate function"`
        - Use a present verb like `Adding`, `Fixing`, etc.
5. Push your changes
    - `git push`
        - If this is your first time pushing on this branch you will get an upstream output
        - Copy the upstream command and paste it into the command line
        - Press enter to commit your first push on this branch
        - This will allow your current branch to pull in "master" changes to keep up with the current build
6. Go to GitHub and create a new Pull Request
7. Add a description of the changes and add yourself as the assignee
    - Also add appropiate tags
8. Add @MatthewPeery or @kgrewal2 as a reviewer
9. Resolve comments and changes during the review
    - The review should be under 24 hrs
10.  Once approved, merge your changes to the "current" branch

### Helpful Git Commands
- `git checkout <branchname>`
    - Checkouts any existing branch including master
- `git pull`
    - Pulls in all of the new changes
       - If you are on a local branch to pull in master changes the upstream must be set
       - If you are on the master branch it will pull in all of the new changes
- `git branch -l`
    - Lists all of the local branches
- `git branch -la`
    - Lists all of the local and remote branches
        - Useful if you need to pull in a remote branch
### README.md
- This should be a flowing document
- All relevent and useful development information should be added to the README.md
    - Diagrams
    - Flows
    - Testing practices and commands
    - Key architecture design
- Useful markdown language guide [markdown](https://www.markdownguide.org/basic-syntax/)

## API Teams
- Mamba
    - The team for the main contibutors and the CODEOWNERS.
    - When in doubt add us to review!
