# Exercise 1 git redo
This is the readme for [exercise 1](https://jktechnosoftltd-my.sharepoint.com/:w:/g/personal/arijit_dalui_jktech_com/EWSF9cuBoClDt9VJ0oLhAgcBkPU3yWtdavvM2zaOM3voxg?wdOrigin=TEAMS-MAGLEV.p2p_ns.rwc&wdExp=TEAMS-TREATMENT&wdhostclicktime=1751988487024&web=1)

## Algorithmic approach
## Steps
1. Initialized empty git repository 
```bash
git init
```
2. Changed branch name to main
```bash
git branch -m main
```
3. Added this readme file and commited
```bash
git add .
git commit -m "added initial readme file"
```
4. Switched to branch named dev/arpan
```bash
git checkout -b dev/arpan
```
5. Created folder group_arpan_aman and changed directory to it.
```bash
mkdir group_arpan_aman
cd group_arpan_aman
```
6. Inside the mentioned folder added two folder and sample files.
```bash
mkdir frontend backend
cd frontend
touch index.html
cd ..
cd backend
touch main.py
cd ../..
```
7. Written some content in sample files and staged the changes and commited it.
```bash
git status
git add .
git commit -m "Added folder and initial files to folder with group name"
```
8. New user first clones the repository
```bash
git clone https://github.com/arpan-jk/exercise1_git-redo.git
```
9. Then the new user staged the changes and commits it
```bash
git add .
git commit -m "changes made by new user"
```
10. A new branch dev/aman is made and switched to that branch
```bash
git checkout -b dev/aman
```
11. Finally the new branch is pushed
```bash
git push -u origin dev/aman
```
## Flow chart
## References
1. How to make a readme file : [link](https://www.makeareadme.com/)
2. How to push,pull and commit requests : [link](https://docs.github.com/en)