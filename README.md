# Learning-Git
This is my personal compendium of the most frequently used Git commands, which serves as a one-stop-shop for all the necessary knowledge I have acquired through Udemy courses, books, YouTube tutorials, and other sources. It also serves as a means to showcase the knowledge I have gained, which can be useful for potential employers.


Initialize a new repository
    git init

After the creation of a git repository on github
copy the SSH link

In order to register and open a connection to the repository on github
    ssh-keygen -t ed25519 -C "your_email@example.com"
the -t ed25519 is the encryption type, the -C is for comment to add the email as a commentary

after the creation on the key, the public key is added to github, the private key is added to the directory
.ssh and use eval "$(ssh-agent -s)" to execute the agen and ssh-add ~/.ssh/yourKey to add a key to the repository

in order to pull form github to update ud git fecht origin first and after a git diff use git merge to combien

dont forget squad merge to leave an added branch with just one commit whitout losign all the commits from the feature branch

change global settings
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"