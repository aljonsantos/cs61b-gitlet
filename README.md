# Gitlet

An implementation a version-control system that mimics some of the basic features of the popular system Git.

## Commands
| Usage                                                      | Description                                                                  |
|------------------------------------------------------------|:-----------------------------------------------------------------------------|
| ```java gitlet.Main init```                                | Initializes current directory as gitlet repository                           |
| ```java gitlet.Main add [file name]```                     | Add file to the staging area                                                 |
| ```java gitlet.Main commit [message]```                    | Make a commit                                                                |
| ```java gitlet.Main rm [file name]```                      | Remove a file                                                                |
| ```java gitlet.Main log```                                 | Display commit history                                                       |
| ```java gitlet.Main global-log```                          | Display global commit history                                                |
| ```java gitlet.Main find [commit message]```               | Finds commit given commit message                                            |
| ```java gitlet.Main status```                              | Displays repo status (current branch, branches, staged files, removed files) |
| ```java gitlet.Main checkout -- [file name]```             | Checkout a file                                                              |
| ```java gitlet.Main checkout [commit id] -- [file name]``` | Checkout a file in a commit                                                  |
| ```java gitlet.Main checkout [branch name]```              | Checkout a branch                                                            |
| ```java gitlet.Main branch [branch name]```                | Create a branch                                                              |
| ```java gitlet.Main rm-branch [branch name]```             | Removes a branch                                                             |
| ```java gitlet.Main reset [commit id]```                   | Reset to a commit                                                            |
| ```java gitlet.Main merge [branch name]```                 | Merge files from the given branch into the current branch                    |



