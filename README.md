# Copy a repository
1. Create a new empty directory and git initialize
  ```bash
  mkdir <project-name>
  cd <project-name>
  git init
  ```
2. Pull the repository to be copied
  ```bash
  # git url is same as the clone URL
  git pull <git-url-of-repo-to-be-copied>
  ```
3. Create a new empty repository
4. Push the directory content to the new repository
    ```bash
    git remote add origin <git-url-of-new-repository> 
    git push -u origin master
     ```
