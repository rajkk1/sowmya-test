# sowmya-test
Test repo to get used to some github commmands

Hello Sowmya! This small exercise will give you an idea of how we use Github to share code. What you'll do is take this "code" (i.e. just this Readme file), edit it, and merge it into the main repo. We will do this in several steps. For each step, I will give you the task and the command to run, but I'll let you figure out exactly how to use those commands (I think Google will be the easiest way!). So here we go!

These first few steps are all done through the _anaconda prompt_ terminal
1. Install git using `conda install git`
2. _Clone_ this repository with the `git clone` command. This will make a local copy of this code repository onto your computer, including all the save history.
3. Make a _new branch_ with the `git branch` command (you can call this new branch whatever you want). This will basically duplicate the current state of the code so that you can work on adding your code and then later _merge_ it with the main code.

For this next step, use whichever text editor you like (e.g. notepad++)
4. Open README.md (i.e. this file) and edit this line such that the following sentence is true: the complete set of Clifford gates consists of just the H and CNOT gates.  

The next few steps are once again done through anaconda prompt
5. Add the README.md file to your local git using the `git add` command and commit your changes using the `git commit` command
6. Push your changes _upstream_ to the GitHub repo using `git push`. This last step will put everything on the github repo

So we're almost done, except now if you come back to the Github repo, you'll notice that the README.md file hasn't changed! That's because your changes are on your branch and not the main branch. So the final step is to make a _pull request_ i.e. request that your changes be merged onto the main branch.
7. Go back to https://github.com/rajkk1/sowmya-test and make a _pull request_ on Github to merge your branch with the main branch

Pull requests are useful for code reviews, because once you make them, Github will show all the differences between your branch and the main branch, and so it's easy for other people to see what changes you've made and to add any comments. Once I check that things look good, I will accept the pull request and you'll be done!


