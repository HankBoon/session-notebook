### Basic Shell commands

| command                            | functionality                                                              |
| ---------------------------------- | -------------------------------------------------------------------------- |
| `ls`                               | list the content of the current directory                                  |
| `cd <foldername>`                  | change directory into a folder                                             |
| `cd ..`                            | change into the parent folder                                              |
| `cd ~`                             | change into your home directory                                            |
| `pwd`                              | print the current directory path                                           |
| `touch example.md`                 | create a file called "example.md"                                          |
| `mkdir newFolder`                  | create a folder called "newFolder"                                         |
| `mv <oldname> <newname>`           | move or rename a file                                                      |
| `rm <filename>`                    | delete a file permanently (there is no trash bin to recover files!)        |
| `open .`                           | open the current folder in the finder                                      |
| `cat <filename>`                   | prints the content of a specific file                                      |
| `curl <url>`                       | prints the received content from the specified url. (try `curl ipinfo.io`) |
| `git status`                       | List all files that have changed and their state                           |
| `git add <filename>`               | Add a file to the stage                                                    |
| `git commit -m "add foo"`          | Create a commit including all staged files                                 |
| `git log --oneline`                | Show the commit history                                                    |
| `git restore .`                    | returns to last comitted point                                             |
| `git restore <filname>`            | restores individual files                                                  |
| `git remote add origin <ssh link>` | connects to remote repository                                              |
| `git remote -v`                    | checks on fetch and push addresses                                         |
| `git push -u origin main`          | defines branch which to push to and pushes commits to remote repository    |
| `git push`                         | pushes commits to remote repsitory                                         |
| `git switch -c <branchname>`       | create a new branch and switch to it                                       |
| `git switch <branchname>`          | switch branches                                                            |
| `git branch`                       | list your branches                                                         |
| `git branch -a`                    | list all branches (local and remote)                                       |
| `git branch -d <branchname>`       | delete a branch                                                            |
| `git clone <repository-url>`       | clones a repository fro that URL into the folder you are in                |
| `npm run start`                    | starts development server on localhost:3000                                |
