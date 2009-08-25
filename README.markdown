Set GIT_SSH to the path to github-ssh

    export GIT_SSH=/path/to/github-ssh/bin/github-ssh

For each repository which has a non-default user, run: 

    git config ssh.identity ~/.ssh/company1.id_dsa

Now you can use normal github urls inside the repositories.
