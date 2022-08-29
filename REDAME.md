# run - `git init`

//makes a `.git` hidden folder.

# run - `git add filename`(just one particular file) // run - `git add ./` (all folders)

//(/ it will add file to the `staging` area/ it will also make a `index` folder in `.git` / `index` folder represent the `staging` area.)

# run `git commit -m "xyx" ` / this is how you commit / and you will see new files in `object` folder it means it got `committ`

# run `git status`

//help us to know wether files are being commited or not

# run `git push`

-------------------------------git hidden files-----------------------------------------

# run - `LS-A`

//shows hidden files.

# run - `LS`

//shows files.

------------------------how to add name and username-----------------------------

# run - `git config --global user.name rob`

# run - ` git config --global user.name masterofbloc@cmail.com`

------------------------------------git branch-----------------------------------------

# run - `git branch`

// shows the total number of branches `*` meaning that we are bein on that branch only.

# run - `git branch branch1`

this is how to add a new branch. `branch1` is the name of sample branch.

# run- `git checkout yes`

// this is how you swtich from one to another branch. `yes` is the same branch name.

# run - `git checkout -b yes`

// this is how you switch working branch.

# run - `git merge yes`

//how to merge. `yes` is the name of the branch.

# run- `git branch -d yes`(this is how you delete)

-------------------------how to check parents -------------------------------------

# run - `git log`

# when you see `:` eneter `wq` and type ` git cat-file -p headmasterfilecommint numbers`

# run again - `git log`

------------------------------hoe to Local and Remote Repo to connect---------------------

# run- `git init`

# run - `git remote add origin repolink`

//`origin` is the name of repo. it could be anything.

//this is how you connect `local` and `remote` work

# run - `git remote`

//will shows the name of added remote repos.

# run -`git push origin master`

// origin is the name of repo.
// master is the name of branch.

# run - `git log`

// will be able to see `origin master` branch as well.

-------------- AFTER pushing -> changes are made to local and push again-----------

# run- git push origin master //run `git log`to check if its being pushed.

---------------------------------------cloning-----------------------------------------

# run- git clone repolink xyz

# now run - `cd xyz`.

//It will make a folder named `xyz` and save the cloned repo in that.`cd` will help to fectch data in `xyz` folder.

------------------------------------------fetch from Github-----------------------------------------------

# run- git fetch origin

# run - git merge origin/master

# run - git log (can see fetched)

-------------pening `pull request`--------

# run - git pull origin master

# git push origin master

# git pull origin master

---

# run- git remote --v

//thats how yu check what files are in totally added.

# run - git remote

//gives you the name of remote

# run - git branch

//gives ya branch name
