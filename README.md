To remove them locally:
git branch -d dev
git branch -d test

To remove them remotely:
git push origin --delete dev
git push origin --delete test

To checkout another branch without commit changes:
git stash
git checkout dev
git stach pop

git stash
git checkout test
git stach pop

To list tag:
git tag ->lists all tags
git tag v1.0 -> lists info about tag called v1.0

To delete tag locally:
git tag -d v1.0

To delete tag remotely:
git push origin --delete v1.0
![image](https://github.com/user-attachments/assets/ca4da1b8-2cd4-44de-83a9-e47fd733b01d)
