# Hello Opensource 

This is your "Hello world" for open source contributions. Want to try practising some PRs? This is the right place!

## Step 1: Fork this repo

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510135-ffa77680-f228-11ea-889f-d4a99eb873db.png" alt="fork this repository" />

This creates a copy of this repo to your GitHub account. Consider a scenario where you want to work with some code from your friend. So you copy the code in a flash drive from your friends PC. Forking is similar to this.

## Step 2: Clone the repo

Now, go to the fork of this repo **on your account**. To work with code, clone that repo to your local machine (as shown below). Similar to copying the code from the flash drive to your system. If you haven't installed the git, then this is the best time to do this - [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) is a guide on installing git

Click on "Code"

<img align="center" src="https://user-images.githubusercontent.com/59721339/92510454-7fcddc00-f229-11ea-9178-eb8cebfd34f7.png" />

Copy the link

<img align="center" src="https://user-images.githubusercontent.com/50027064/102229988-5ac8c380-3f12-11eb-97b7-6cd551129ff2.png" />

To clone the repo, open the terminal and run the command

```
git clone "url-you-copied"
```

Now you have the project repo on your local machine.

## Step 3: Create a new branch

 Go to the repo directory on your machine
 
 ```
 cd Hello-opensource
 ```
 
 Create a new branch (It is a good practice to create a new branch if you wish to contribute)
 
 ```
 git checkout -b <branch-name>
 ```
 
 for example:
 
 ```
 git checkout -b add-bruce-wayne
 ```
 
 Why create a new branch?
 You don't want to mess the code your friend has already written. By creating a new branch, you can safely work on top of the friend's progress. 
 
<img align="center" src="https://user-images.githubusercontent.com/59721339/92589146-bf430980-f2b7-11ea-9dc2-3581c1ea610c.png" />

## Step 4: Create a new file

Go to contributions folder
```
cd contributors
```

Create a new file in that directory and fill in your info.

For example:
```
Name: Bruce Wayne
Github: [batman](https://github.com/batman)
```
Save as `<your-name>.md`

## Step 5: Commit changes

 If you finalise the changes you can store the changes permanently by two steps
 
 - `add` the changes
 ```
 git add <filename>
 ```
 - `commit` the changes
 
 ```
 git commit -m "Add <your-name> to contributors"
 ```
 
## Step 6: Push changes

Push the changes to your repo by:

```
git push origin <your-branch-name>
```

From our example, we had already copied the files from the flash drive. We made some changes. Now we are copying back the changed file to flash drive so that we can give our changes to the friend.

## Step 7: Create a pull request

Here you're giving the flash drive to your friend. So he/she can look into the changes you have made. If everything is good, he/she can have the changes you made to his/her project.

First, go to the GitHub repo in your account. Click `Compare & pull request`

<img align="center" src="https://user-images.githubusercontent.com/59721339/92591860-46927c00-f2bc-11ea-98d1-3d1f56d76ec1.png"/> 

And submit the pull request by clicking `Create pull request`

<img align="center" src="https://user-images.githubusercontent.com/59721339/92592170-cc162c00-f2bc-11ea-9e40-ac4afc618c6d.png"/>

## Hurray!

 Congratulations, you have made it. Got any doubts? Feel free to let us know at our Discord!

## Summary 

<pre>
 fork ----> clone ----> make changes -- +
                                        | 
create a PR <---- push <---- commit <-- +
</pre>

## Addditional resources

Check out this [link](https://openhack.gitbook.io/openhack-20/resources#git-and-github) if you would like to explore more!
