# Git command you need to know
-- If you create git repository direct from you computer you need to initiate git repository first with following command
>`git init`
> -- And then check the status first with following command
>`git status`
> -- But if you clong the git reposity from the github then you don't have to initialize the git repository since it is already initiated
# How to create a branch
> There are two command to create a branch
> First git branch and give the whatever name you want to create like
`git branch project`
> And this command will only create a branch but git checkout -B command will create the branch and same time it will change your current branch to your created branch too like
` git checkout -B project`
# How to get the git list
> To check and confirm the current branch you are in.
`git branch`
> This command will show you the branch and highlighted your current branch
> But if you want to back to the previous branch. you can use following command
`git checkout master`
>`git branch -a`
>`git remote show practicw`
>`git add test.txt`
>`git commit -m "test file comminted to git version control repostrory"`
>`git status`
>`git branch`
> -- If your git branch output in less and you want direct output on terminal then run the following command
>`git config --global core.pager cat`
>`git branch`
>`git status`
>`git commit -am "test file commited to git repostory"`
>`git add test.txt`
>`git commit -m "test file commited to git repositry"`
>`git remote add origin https://github.com/dawalhasa/practicw.git`
>`git remote add master https://github.com/dawalhasa/practicw.git`
>`git remote add feature/lesson`
>`git checkout -B master`
>`git push -u origin master`
>`git remote add feature/lesson  https://github.com/dawalhasa/practicw.git`
>`git checkout -B feature/lession`
>`git push -u origin feature/lession`
