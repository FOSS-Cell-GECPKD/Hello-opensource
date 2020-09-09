# Hello Opensource 

[Intro]
This is your "Hello world" for opensource contribution. Want to try out some PR, this the right place.[more intro]

## Step 1: Fork this repo

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510135-ffa77680-f228-11ea-889f-d4a99eb873db.png" alt="fork this repository" />

 This creates a copy of this repo to your github account. Consider a scenerio were you want to work with some code from your friend. So you copy the code in a flash drive from your friends PC. Forking is similar to this.
 *more explanation*
## Step 2: Clone the repo
Now  you got the repo on your account.To work with code, clone the repo to your local machine. Similar to copying the code from the flash drive to your system. If you haven't install the git, It is a best time to do this.

**Step 2.1: Click on the "Code"**

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510454-7fcddc00-f229-11ea-9178-eb8cebfd34f7.png" />

**Step 2.2: Copy the link**

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510575-b3a90180-f229-11ea-8c77-4f90752647ea.png" />

## Step 3: Create a new branch
 Go to the repo directory on your pc
 `cd hello-opensource`
 Create a new branch
 `git checkout -b <branch-name>`
 for example:
 `git checkout -b add-bruce-wayne`
 // TODO: explain in beginning what we are going to do.
 why create a new branch?
 You don't want to mess the code your friend have already written. By creating new branch, you can safely work on top of the friend's progress. 
*explantion*
## Step 4: Create a new file
Go to contributions
`cd contributions`

create a new file in that directory and fill in some info.

For ex:
  <example>
*explanation*
## Step 5: Commit changes
 If you finalise the changes you can store the changes permanently by two steps
 - `add` the changes
 `git add <filename>`
 - `commit` the changes
 `git commit -m "Add <your-info> to contributors"`
 
*explanation*
## Step 6: Push changes
Push the changes to your repo by:
`git push origin <add-your-branch-name>`
from our earlier example we copied the files from the flash drive. We made some changes. Now we are copying back to flash drive, So we can give our changes to friend.
*explanation*
## Step 7: Create a pull request
*explanation*
Here you give the flash drive to your friend. So he can look into the changes you have made. If everthing is good, he can have the changes you made to his project. 
## Hurray!
 Congratulations, you have made it. Got any doubts, we are here to help you [gitter].

## Summary 
<pre>
 fork ----> clone ----> make changes -- +
                                        | 
create a PR <---- push <---- commit <-- +
</pre>
## Addditional resources
If you want to explore git more here are few resources that  could help you
