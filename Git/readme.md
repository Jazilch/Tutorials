These commands are well documented on GitHub but if you are just trying to dive into these commands they can seem intimdating and now make much sense. 

Below is how you're able to create and setup new repisitories into GitHub. What this doesn't tell is you first need to be
in a working directory in order to run these commands. See my command line prompts in order to create a working directory
and once you've created this directory see my comments below

If you're creating a new repisitory then you will want to use this command in order to create a new repisitory. See comments
…or create a new repository on the command line
echo "# test" >> README.md
 tell the document to expect information from git
git init
add the README.md file from above into a tracked file
git add README.md 
setting your first commit to git
git commit -m "first commit"
setting the origin of the URL of yuor GitHub directory. This is how the local directory knows to speak to the GitHub Cloud Enviornment
git remote add origin https://github.com/Jazilch/test.git .
Push those files live
git push -u origin master 


…or push an existing repository from the command line

git remote add origin https://github.com/Jazilch/test.git
git push -u origin master


use this command in order to check your current files and if they are currently being tracked.
git status

If you see untracked files then use the command below to add these as tracked files
git add README.md




https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository
