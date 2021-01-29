# HRCI_ichigaya



## Git編集履歴の全削除方法
```
git checkout --orphan temp
git add -A
git commit -am "init"
git branch -D master
git branch -m master
git push -f origin master
```
