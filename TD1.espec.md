## TD1: Setup

1. Download and Install **git** and **RStudio** (take the free version)
   - Git: https://git-scm.com/downloads
     - _Understand git and Tutorial_: https://try.github.io/
   - RStudio: https://www.rstudio.com/products/rstudio/download/

2. Create a github account
   - https://github.com/join
     - Use as **login** something that uniquely identify yourself in Miage L3.
   - Login with your new account in the http://github.com/

3. Add your public SSH key
   - Add it here: https://github.com/settings/keys
   - _Tutorial_: https://help.github.com/articles/connecting-to-github-with-ssh/


4. Fork the reference repository
   - Fork this repository: https://github.com/schnorr/proglitt
     - Please, use the `Fork` button in the web interface
   - _Tutorial_: https://help.github.com/articles/fork-a-repo/

5. Clone your forked repository locally
   - `git clone git@github.com:LOGIN/proglitt.git`
   - _Tutorial_: https://help.github.com/articles/cloning-a-repository/


6. Create your first commit, then push it to github
   - Create a file `AUTHOR.txt` with your name
   - Then, run `git add AUTHOR.txt`
   - Commit it locally using `git commit -m "my first commit"`
   - Push to github with `git push origin master`

7. Add Prof. Schnorr's remote

   Do in your local repository, the one that you've cloned, the following commands:
   
   - Run `git remote add schnorr git@github.com:schnorr/proglitt.git`
   - Check for updates: `git fetch schnorr master`
   - Merge them locally: `git pull schnorr master` (pull is equivalent to fetch+merge commands)
   - Push then to your github repository: `git push origin master`

   Repeat the last two commands to keep your github repository updated.

   This is necessary to keep yourself up to date with latest TD updates.

   
Congratulations, you're done for the TD1.