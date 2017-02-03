# Literate Programming Course

Welcome to the Literate Programming public repository, part of the Miage L3.

## Presentations

- [General Introduction](./Presentation/0-Introduction/Transp-Prog-Lit-2017.pdf) - Course overview, goals, references and reproducibility
- [Literate Programming](./Presentation/1-LitProg/1_LitProg.pdf) - Literate Programming Motivation & RStudio Case Study

## TD Specifications

### TD1: Setup

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

### TD2: Critical view for plots

1. Create a directory `TD2` in your local repository
   - Run `mkdir TD2`
   - You are going to put your TD2 on that directory

1. Select a plot
   - Select any plot you have seen in journals/articles/...
   - Create a text with your **critical view** on that plot
     - Is the plot right? What about the axes, are they explicit?
     - Are the scales correct? Is the origin there?
     - What about the colors, shapes of the points?

2. Commit the **plot** you have selected and your **critical view** to the `TD2` directory

   Suppose your critical view is on the file `myTD2.txt` and the plot is `mySelectedPlot.pdf`, do:
   - `cd TD2`
   - `git add myTD2.txt mySelectedPlot.pdf`
   - `git commit -m "my TD2 has been completed"`

Congratulations, you're done for the TD2.

### TD3: Using RStudio for running a Statistical Analysis

See the [Specification for the TD3](./TD3/TD3.Rmd). You need to repeat
the analysis that has been presented for one of the provided data
sets: ping-pong measurements or the iteration duration of a geophysics
application. You need to use RStudio to modify the given file, writing
in your data interpretation of the results, and generating a PDF file
at running knitr in the document (through the appropriate feature in
RStudio).

### TD4: Forthcoming

## Contact Information

If you encounter any problem, please contact the professors by e-mail:
- Jean-Marc Vincent (jean-marc.vincent@imag.fr)
- Lucas Mello Schnorr (schnorr@inf.ufrgs.br)
