# Undoing Things
```
to Revert changes on Git, you can use
```
## 1
```
git checkout {Your_Changes_File}
```
![](../docs/img/sshot-10.png)


## 2
```
touch newfile.txt
git add *
git status
git reset HEAD newfile.txt
git status
```
![](../docs/img/sshot-11.png)

## 3
```
git add newfile.txt
git commit -m "add new script"
git add another-newfile.txt
git commit --amend
```
![](../docs/img/sshot-12.png)

## 4
```
git commit -a -m "new"
git revert HEAD
```
![](../docs/img/sshot-13.png)

## 5
```
git log -2
git show {commit_id}
git revert {commit_id}
```
![](../docs/img/sshot-14.png)