# codingdemo
Practicing using git commands. What I learned. 

1) Setting up an SSH Key: https://docs.github.com/en/enterprise-server@3.0/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#adding-your-ssh-key-to-the-ssh-agent
2) Adding Extentions to Visual Studio so as to help me with developing my thoughts faster.
3) Using GitBash (which I have avoided because I have cmd line. 
4) Setting up github so that I am using an SSH key when submitting my code. That way my computer can talk to github w/o having to login every single time.
5) In github, some of the more common, day-to-day, "activities":

Setting up New Repository
    a) +, New Repository, use SSH, copy address
    b) go to root directory using bash
    c) git clone <SSH address copied in step a>
    
Saving Modifications to git (AKA pushing changes)
    a) open .
    b) cd <repository's name>
    c) git add -A
    d) git commit -m "<short description of changes>"
    e) git push origin main     
    
Creating a new branch (AKA branching)
    a) git checkout -b <nameOfNewBranch>  (a code check should be accomplished before merge of branch!)
    b) do modification, save in VS (or whatever GUI you are using)
    c)	git add -A 
    d)	git commit -m “added h1 tag”
    e) git push origin <NameofNewBranch>
    Your changes will be on a new branch in the repository.
    
Merging to main
    a) compare and pull request/new pull request/create pull request.
    b) validate that the code looks okay (this will be done by one of your team members)
    c) merge pull request button
    d) validate that the pull request was 'successfully merged and closed' and delete branch.
    
More changes? You want to use main?
    a) git checkout main
    b) git pull (changes are moved to VS)
