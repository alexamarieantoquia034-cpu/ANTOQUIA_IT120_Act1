Git Command used:

1. git init
2. git add .
3. git commit -m "Initial commit with Profile, Education, Background, Readme, Test files"

#Branch B1
4. git branch ANTOQUIA_B1
5. git checkout ANTOQUIA_B1
6. git add Profile.txt
7. git commit -m "Added Birth Place, Religion, and Parents info in Profile.txt"

#Branch B2
8. git checkout master
9. git branch ANTOQUIA_B2
10. git checkout ANTOQUIA_B2
11. git add Education.txt
12. git commit -m "Added College, Program, and Year Level in Educatioon.txt"

#Branch B3
13. git checkout master
14. git branch ANTOQUIA_B3
15. git checkout ANTOQUIA_B3
16. git add Background.txt
17. git rm Test.py
18. git commit -m "Added Person to be Contact and Address in Background.txt and removed Test.py"

#Branch B4
19. git checkout master
20. git branch ANTOQUIA_B4
21. git checkout ANTOQUIA_B4
22. git add Readme.txt
23. git rm Test.py
24. git commit -m "Added Git commands in Readme.txt and removed in Test.py"

#PUsh to GitHub
25. git remote add origin https://github.com/alexamarieantoquia034-cpu/ANTOQUIA_IT120_Act1.git
26. git push -u origin master
27. git push origin ANTOQUIA_B1
28. git push origin ANTOQUIA_B2
29. git push origin ANTOQUIA_B3
30. git push origin ANTOQUIA_B4

#Branch merged into master
31. git checkout master
32. git merge ANTOQUIA_B1
33. git merge ANTOQUIA_B1
34. git merge ANTOQUIA_B3
35. git merge ANTOQUIA_B4
36. git push origin master

