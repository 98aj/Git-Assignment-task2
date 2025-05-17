Commands for GIT Assignement task 2 are as follows

Task 2:

1. mkdir task2
2. git init
3. touch feature1.txt feature2.txt (created on master branch)
4. git status
5. git add feature1.txt feature2.txt
6. git commit -m 'Inital commit to master branch'
7. git remote add origin https://[secret-key-token]@github.com/98aj/Git-Assignment-task2.git
8. git push -u origin master
9. git branch develop   git push origin develop (to push local branch to github)
10. git branch feature1  git push origin feature1 (to push local branch to github)
11. git branch feature2  git push origin feature2 (to push local branch to github)
12. git switch develop
13. touch develop.txt
14. git stash -u
15. git switch feature1
16. touch new.txt
17. git add new.txt
18. git commit -m 'New file created at feature branch'
19. git push -u origin feature1
20. git switch develop
21. git stash pop
22. git add develop.txt
23. git commit -m 'Commiting develop file from develop branch'
24. git push -u origin develop
