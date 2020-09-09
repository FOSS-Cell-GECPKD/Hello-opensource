# Hello Opensource 

[Intro]
This is your "Hello world" for opensource contribution. Want to try out some PR, this the right place.[more intro]

## Step 1: Fork this repo

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510135-ffa77680-f228-11ea-889f-d4a99eb873db.png" alt="fork this repository" />

 This creates a copy of this repo to your github account. Consider a scenerio were you want to work with some code from your friend. So you copy the code in a flash drive from your friends PC. Forking is similar to this.
 *more explanation*
## Step 2: Clone the repo
Now  you got the repo on your account.To work with code, clone the repo to your local machine. Similar to copying the code from the flash drive to your system. If you haven't install the git, It is a best time to do this.

Click on the "Code"

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510454-7fcddc00-f229-11ea-9178-eb8cebfd34f7.png" />

Copy the link

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510575-b3a90180-f229-11ea-8c77-4f90752647ea.png" />

To clone the repo, open the terminal and run the command.

```
git clone "url-you-copied"
```
Now you have the project repo on your local machine.

## Step 3: Create a new branch

 Go to the repo directory on your machine
 
 ```
 cd Hello-opensource
 ```
 
 Create a new branch (Always create a branch if you wish to contribute)
 
 ```
 git checkout -b <branch-name>
 ```
 
 for example:
 
 ```
 git checkout -b add-bruce-wayne
 ```
 
 why create a new branch?
 You don't want to mess the code your friend have already written. By creating new branch, you can safely work on top of the friend's progress. 
 
<img align="center" src="https://user-images.githubusercontent.com/59721339/92589146-bf430980-f2b7-11ea-9dc2-3581c1ea610c.png" />

## Step 4: Create a new file
Go to contributions
```
cd contributors
```

create a new file in that directory and fill in your info.

For ex:
```
Name: Bruce Wayne
Github: [batman](https://github.com/batman)
```
Save as `<your-name>.md`

## Step 5: Commit changes
 If you finalise the changes you can store the changes permanently by two steps
 `add` the changes
 ```
 git add <filename>
 ```
 `commit` the changes
 
 ```
 git commit -m "Add <your-name> to contributors"
 ```
 
## Step 6: Push changes
Push the changes to your repo by:

```
git push origin <add-your-branch-name>
```

from our earlier example we copied the files from the flash drive. We made some changes. Now we are copying back to flash drive, So we can give our changes to friend.

## Step 7: Create a pull request

Here you give the flash drive to your friend. So he can look into the changes you have made. If everthing is good, he can have the changes you made to his project.

First go to the github repo in your account. Click `Compare & pull request`

<img align="center" src="https://user-images.githubusercontent.com/59721339/92591860-46927c00-f2bc-11ea-98d1-3d1f56d76ec1.png"/> 

And submit the pull request by clicking `Create pull request`

<img align="center" src="https://user-images.githubusercontent.com/59721339/92592170-cc162c00-f2bc-11ea-9e40-ac4afc618c6d.png"/>

## Hurray!
 Congratulations, you have made it. Got any doubts, we are here to help you [gitter](https://gitter.im/FOSS-Cell-GECPKD/community).

## Summary 

<pre>
 fork ----> clone ----> make changes -- +
                                        | 
create a PR <---- push <---- commit <-- +
</pre>

## Addditional resources
If you want to explore git more here are few resources that could help you
- [Git Tutorial for Beginners](https://www.youtube.com/watch?v=PWqS4NBhEY8) 
- [GitHub flow](https://guides.github.com/introduction/flow/)
- [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123) 
