"# forwardSchoolGitAssignment" 

<h1 align="center">Git Exercise</h1>

<!-- Table of Contents -->
### Table of Contents'S
<li>
    <a href="#Generating new SSH Key">Generating new SSH Key</a>
</li>
<li>
    <a href="#Instruction">Instruction</a>
</li>

<!-- Generating new SSH Key -->
### Generating new SSH Key
* You can create a new SSH key by opening CMD prompt, and type the following code.
```sh
    ssh-keygen -t rsa
``` 
* You also need to type a passphrase to use it later.

<!-- Instruction -->
### Instruction
This is how i created this repository

1. In VS Code, I've created a new folder called gitAssignment and change the directory to it.

    ```sh
    mkdir gitAssignment
    cd gitAssignment
    ```

2. Then I begin to initialise the git at this folder.

```sh
    echo "# gitAssignment" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -m main
    git remote add origin git@github.com:kvtang1511/forwardSchoolGitAssignment.git
    git push -u origin main
```
3. Next I created new file in VS code under gitAssignment folder and add some text.
4. Then I pushed everything to respo.

```sh
    git add .
    git commit -m "comments"
    git push
```

5. That's it :)