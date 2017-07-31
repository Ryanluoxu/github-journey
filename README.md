# Github-Journey

- I will share my github journey here for anyone who just starts his/her github.
- Please advice me if you got any suggestion

## Part 1 - Write a simple document on github
### Step 1
Go to any popular community, get rough idea of github.
- Go to [知乎](http://www.zhihu.com)
- Search 'github'
- Spend a few hours to just go through different related topic

### Step 2
- Create a github account.

### Step 3
- Search 'markdown' in github, I am sure there is tons of useful information
- I will recommend [献给写作者的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)

### Step 4
- Go to github, create a new repositoty called: 'Interview Questions'
- In `README.md`, use Markdown syntax to write a documents of 30 interview questions.

### Step 5
- Invite `willsanity` to create an account and `follow` each other.
- Ask him to join 'Interview Questions' using `fork`. Add something and `pull request`. 
- `merge pull request`, so the change made by `willsanity` is updated to the `master`.

## Part 2 - Upload a project to Github using CMD
From: [Answers of Jokab on SO](https://stackoverflow.com/questions/17552457/how-do-i-upload-eclipse-projects-to-github)
1. Download `git` from [http://git-scm.com/](http://git-scm.com/)

2. Create `optimumDemo` repo on github.

3. On machine, `run` - `cmd`, navigate to the project folder: 
> `cd C:\Batch3\demo`

4. Initiate a new git repo in the folder: (No result there)
> `git init` 

5. Register the new repo with a remote which is `optimumDemo` repo on github
> `git remote add origin https://github.com/Ryanluoxu/optimumDemo.git`

6. Add all files to my local commit:
> `git add .`

7. Make an initial commit:
> `git commit -a -m "Initial commit"`

8. Push
> `git push -u origin --all`

9. Small window come out. Enter username and password. Done

## Part 3 - Upload a project from Eclipse to Github
From: [Answers of Aparna on SO](https://stackoverflow.com/questions/17552457/how-do-i-upload-eclipse-projects-to-github)
Upload my Banking System project as an Example. Install git first.
In Eclipse, 
1. Right click on `WebBankingSystem` -> `Team` -> `Share project`
2. Unclike `Use or create repo in parent folder of project`
3. `Create...` -> `C:\Users\Ryan.luo\WebBankingSystem`-> `Finish` (This will create a local git repo)
4. Right click on `WebBankingSystem` -> `Team` -> `Commit`
5. Drag 'WebBankingSystem' from `Unstages Changes` to `Staged Changes`(Select only the files you want to commit)
6. Click on Commit. (Now the files are committed to your local repo)
7. Right click on `WebBankingSystem` -> `Team` -> `Show in repositories View`
8. Right click on `Remotes` -> `Create Remote`
9. Remote name will appear as `origin`, select `Configure Push` Option and click `OK`
10. In the next dialog, click on `Change...` and give your git url, username, password and click on `Finish`
11. `Save and Push`, login again. (This configures git Push)

***
> For configuring Fetch, go to Git Repositories -> Remote -> Configure Fetch -> Add -> Master Branch -> Next -> Finish -> Save and Fetch
> For configuring Master Branch, Branch -> Local -> Master Branch -> Right click and configure branch -> Remote: origin and Upstream > > > Branch : refs/heads/master -> click ok
> On refreshing your repo, you will be able to see the files you committed and you can do push and pull from repo.

Possible error:
- `[rejected - non-fast-forward]` [Solution](https://help.github.com/articles/dealing-with-non-fast-forward-errors/)
  
- `[rejected - fetch first]` [Solution](https://stackoverflow.com/questions/28429819/rejected-master-master-fetch-first)

// to be continue
