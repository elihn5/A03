# A03
Part 1: Using Github

  **Github** is a useful location to spread and share your code! To walk through its usage, we will interact with a new **repository**. On your profile page, there is a page for all your repositories. After you create one, you will receieve a mostly blank folder. First, we will create a new file inside this repository (Add file > Create new file...). We will create a .txt file for simplicity. In order for us to create this file, we must **commit** it. Write a brief description for what we have done so far -- in this case, maybe "Created a new text file". Normally, you would click Commit, but let's instead take the opportunity to create a new **branch**, creating a **pull** request in the meantime. By doing this, we essentially have created a new split off repository of the main repository, housing our newfound text file. This is good for making modifications to larger projects without directly modifying the master code, which can be risky. We don't have much reason for this text file to only be in this branch, so let's **merge** it into the main branch by clicking the merge button. Merges can be useful to get everyone on the same page when you're sure that the modified code housed in the remote branch works, but beware of **merge conflicts**, which result from contradictions between the content in the main branch and the side branch we've just created. Nothing of that sort exists here, thankfully, so we'll just merge it now. This concludes the rough overview of how to use the main features of Github!"
  
Part 2: Using WebStorm

**WebStorm** can be a useful tool when dealing with making web-based code of any kinds. It also directly interacts with **Git**, which we will deal with more directly later. It can be downloaded from https://www.jetbrains.com/webstorm/download/ . For now, the basics. First, create a new project, named whatever you want (I just went for "test"), and right click the newfound project folder in the sidebar to create a new HTML file. Again, name it whatever you want. WebStorm is pretty friendly, so we actually get some boilerplate created automatically for us! Let's leave it mostly as it is, but add some quick h1 text so that we know that the website works. WebStorm also fills in the closing tabs for tags that need them, which is pretty convenient too.

Part 3: Using GIT

Git is, among other things, a way to interact with Github via a program. First things first: download it from https://git-scm.com/downloads . After you've done that, open up WebStorm to your project from earlier, and click on the VCS toolbar at the top of the window. From the dropdown, click "Enable version control integration" and select Git as the method to do so. Afterward, the VCS menu should switch to Git.  We can now treat our Github repository as a **remote** repository: one that's hosted on the internet. First, though, we've gotta connect to it! Click the Git drop-down, and then the Clone option towards the bottom. Copy-paste in the URL of your Github repository, and then log in via Github to validate the connection. From here, we can interact with our repository in a ton of different ways. Let's now **clone** its contents, downloading the repository to our hard drive. We can now either **fetch** or **pull** the repository to sync the real copy up with our clone if someone makes changes while we're working on our local copy. Now that we've done that, let's add our test.html to the Github repository! First, we have to **commit** the new file creation, similar to how we had to in Part 1. Next, we **push** the commit to the Github repository, and there it is! This is the absolute basics of using Git, but it should make it easier to interact with a larger project in the future.

Part 4: Glossary
Branch  - an alternate version of a repository, usually created to test out changes before they are folded into the main, "master", repository.
Clone  - A specifically local, offline version of a repository.
Commit  - A change to a repository or file. "Committing" is the act of putting these changes into reality.
Fetch  - Updating your copy of a repository or file by "downloading" the changes made by other users, and holding them for approval. Comparable to fetching, but fetching does not automatically update your copy of the file.
GIT  - An open source program, created by Linus Torvalds, used to track editing in different files.
Github  - An online hosting platform that interacts with, and typically uses, Git. It can be used to syncronize software development.
Merge  - The act of combining a branch with the repository it was created from.
Merge Conflict  - A contradiction between two versions of the same file in different branches, encountered when someone attempts to merge the two branches. Often results from different changes to the same sections of code.
Push  - The act of sending the changes you have made to the main repository. 
Pull  - Updating your copy of a repository or file by "downloading" the changes made by other users, and integrating them into your copy of the file. Comparable to fetching, but pulling automatically changes your copy of the file.
Remote  - a secondary copy of a repository, possibly for backup or for personal use
Repository  - The "folder" that contains your project.

Part 5: Resources
https://docs.github.com/en/get-started/quickstart/hello-world
https://github.com/git-guides/git-push
https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html#put-existing-project-under-Git 
https://www.gitkraken.com/learn/git/tutorials/what-is-git-remote
https://www.atlassian.com/git/tutorials/syncing/git-fetch
https://git-scm.com/docs/gitglossary
https://docs.github.com/en/get-started/quickstart/github-glossary
