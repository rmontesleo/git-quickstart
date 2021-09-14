# Collaboration

## Setup you environment

### Create a git project on GitHub
```
```

### Create a local folder and clone your repository
```
```

---

## Segment 1. Creating branches

### Create a new branch
```
git branch my_first_branch
```

### Check you have the new branch
```
git log --oneline
```

### Switch to the new branch
```
git switch my_first_branch
```

### in some previous versions of git you have to use checkout to switch of branch
```
git checkout my_first_branch
```


### check what happened
```
git log --oneline
```
---

## Segment 2. Making commits in branches

### Type some changes in your files and the, execute the git flow to commit
```
git add .
git commit -m "udpating files, but this time in branch"
```

### check 
```
git log --oneline --graph --all
```

---

## Segment 3. Moving around different branches

### returning to main. If you didnt commit your changes, git does not allow you to switch
```
git switch main
```

### check the content of main

### check the logs in main
```
git log --oneline
```

### return to first branch
```
git swith my_first_branch
```

---

## Segment 4. Merging branches

### Open your pull request
```
1) click on branch link
2) new pull request
```



---

## Segment 5. Merging branches with remotes


---

## Segment 6. Pull requests (aka merge requests)


--

## Segment 7. Syncing up with your remote

--

## Segment 8. Multiple branches

---

## Segment 9. Incorporating hot fixes

---

## Segment 10. Discuss how the skills you learned directly apply to collaboration with other people


---
