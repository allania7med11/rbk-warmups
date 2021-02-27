# Warmups Cohort12
## 1. Fork :twisted_rightwards_arrows:
From the organization, click on the fork button at the top right corner.

![alt text][fork]

[fork]: https://i.imgur.com/krIm9jT.png

## 2.Clone
#### 1. Get the Link of the repo
From you GitHub account, find the forker repository and copy its link by clicking on the green button.

![alt text][clone]

[clone]: https://i.imgur.com/M4wA185.png

#### 2. Cloning the fork to your machine
So far, the forked repository only exists on GitHub. In order to work on the warmups, you will need to clone the repository to your machine.

Open your terminal and clone the repository on your local machine:
```
# Clone your fork to your local machine
git clone <repo_link>
```
## 3. Work on your warmups
After cloning succesfully, navigate to the new cloned folder and start working on the warmups using your favorite text editor. Make sure to test your solution using your browser's console.

## 4. Pushing your work
#### 1. Stage and commit
When finished with the exercice, you must stage the changes using `add` and commit them using `commit`.
Open your terminal and type the following commands:
```
# Staging your changes
git add .

# Commit your changes
git commit -m "YOUR_GIT_COMMIT_MESSAGE"
```
#### 2. Push
Now, you need to push your work to your GitHub repository using the `push` command
In your terminal type the following:
```
# Push you work
git push origin master
```
## 5. Create a Pull Request
Navigate back to the forked repository on your GitHub account, from the top menu click on *Pull requests* and make sure to **change the base branch from master to your branch that has your name**

![alt text][pr]

[pr]: https://i.imgur.com/1d8WKMU.png

## 6. Update your local repository
Everyday, your going to have to work on a new warmup, to make sure that your cloned repository is up to date, each day when we announce a new warmup to must `pull` the updates from the organization repo. To do so you need to do the following:
#### 1. Make sure that you have the required remotes
Open your terminal and type
```
git remote -v
```
You must see two remotes. If you only see something like this:
![alt text][remote]

[remote]: https://i.imgur.com/UcJByoN.png
Then you must add the organization's repo to your work.
Navigate to your warmup folder and open your terminal and paste the following:
```
# Add the upstream remote to your project
git remote add upstream https://github.com/hackreactor/rbktn12-warmups.git
```
#### 2. Update your remote
Inside your warmup folder, open your terminal and use the `pull` command to get the new warmup.
```
# Pull the new warmup from the upstream
git pull upstream master
```
You've successfully pulled the new warmup, happy hacking!
