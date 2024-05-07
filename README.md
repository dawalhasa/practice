# Git command you need to know
> If you create git repository direct from you computer you first need to initialize git repository using following command
>`git init`
> And then check the status by using following command
>`git status`
> But if you clong the git reposity from the github then you don't have to initialize git repository since it is already initialized
# How to create a branch
> There are two command to create a branch
> First git branch and give the whatever name you want to create like
>`git branch project`
> And this command will only create a branch but git checkout -B command will create the branch and same time will change your current branch to your create branch too like
>` git checkout -B project`
# How to get the git list
> To check and confirm the current branch you are in.
>`git branch`
> This command will show you the branches and highlighted your current branch
# How to change branch from one to an another 
>`git checkout master` __This command will simply change your command with branch name you have provide__
# How to __Modity__ your repository
> After completion of your project work you can __Modify__, __Staging__ and __Commit__ your code to local repository
> To __Motidy__ your file you have to add the file to git repository using following command
>`git add project`
> Afther added your project to __local repository__ and you found out some mistake that you wanna undo from the staging state
>`git restore staging project` __You can use this command and undo your staging__
> This command will undo your add
> But if you think your project is correct you can commit git repository using following command
>`git commit -m "Commit Projet"`
> Remember always try to give a meaningful commit message since this is your reposity subject and it will appear on your __Github__
> Then check your status again
# How to list all the __Remote Branches__
>`git branch -r`. __Lists all the remote branches.__
>`git branch -r -v`. Lists all the remote branches with the latest commit hash and commit message.
>`git ls-remote`. Lists all the references in the remote repository, including the branches.
>`git remote show [remote_name]`. Shows information about the specified remote, including the remote branches.
>`git branch -a`. Shows all the local and remote branches.
>`git status`
> If there is no problem indication in your status checking you can push your project to your remote reposity
> But if you are first time try to push your local repository to your remote repository
> Then you have to configure your git --global user.name and email by using following command
>`git config --global user.name=<what every your name you have registered>`
>`git config --global user.email=<what every the email you have registered>`
> Yes one thing to make sure is whether you wanna use to connect your remote repository using __API__ or __SSH__ and __Github CLI__ 
> I generally use __API__ 
> __API__ is a application and method __Githup__ use __API__ is __HTTPS__
> https://github.com/yourname/projectname.git
> Very simple you know github.com and you also know your user name, of course the project and repository that you create you can remember pus extension is .git that all
> For constent user __SSH__ is good but I found there is a security related issue and keep asking for update againa and again. Thats annoying
> And I never used __Github CLI__ method. I'm zero knowledge about that but I think thats also very easy becuase of CLI. Means it should work on command and command once when you acquented no need to worry at all.
> Here in this project just introduce how to connet your remote repository throught __API__
> Before your push your local repository to remote repository you have to add your local new branch repository to remote repository using following command
>`git remote add project  https://github.com/project/project.git`
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
>`git checkout -B feature/lession`
>`git push -u origin feature/lession`
