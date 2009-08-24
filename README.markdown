Set GIT_SSH to the path to github-ssh

    export GIT_SSH=/path/to/github-ssh/bin/github-ssh

For each repository which has a non-default user, run: 

    git config github.user company1

Then make sure you have a SSH vhost called 'github-company1'

    Host github-company1
      HostName github.com
      User git
      IdentityFile ~/.ssh/company1.id_dsa

Now you can use normal github urls inside the repositories.
