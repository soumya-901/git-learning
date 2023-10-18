# Git-learning

- To revert latest git commit in locally use the below command :

```sh
 git reset --soft HEAD~1
```
--soft flag is use , if you want to keep unstaged changes 
--hard flag is use , if you want to remove all unstaged changes 
HEAD 1 , refers to last commited one , simillary HEAD 2 , flag heads to the last 2nd commit
- To revert pushed commit 

```sh
git revert <commit id>
```
you can find commit id by running the command 
> git log

- To edit commited git message locally ,
```sh
git commit --amend
```
then press enter button .
- To edit commit message afted pushing to origin
```sh
git commit --amend -m "New message"
git push --force repository-name branch-name
```
- If you already pushed then it's not recommended to change those commit message coz people who have your commit message then have to change it manually.
