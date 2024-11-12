//overview of the commands used; The serial number here is not the question; 

1. git --version, git init
2. git config --global user.name "Aditya Yadav"
3. git config --global user.email "adityay@iitbhilai.ac.in"
4. cat ~/.gitconfig
5. mkdir my-repo
6. cd my-repo
7. git init
8. echo "print('Hello, World')" > hello.py
9. git add hello.py
10. echo "print('we are IIT Bhilai')" >> hello.py
11. git diff
12. git add hello.py
13. git diff
14. git commit -m "Initial commit with sample code"
15. git log
16. used SSH keygen and git remote origin command to setup us remote repo
17. git remote add origin https://github.com/Lazypilottt/repo1_lab14_12340100.git
18. //another repo for the same user
    mkdir my-second-repo
    cd my-second-repo
    git init
19. echo "Changes in file2" > file2.txt
    git add file2.txt
    git commit -m "Add file2 with changes"
    git push origin main

20. git checkout -b add_readme
21. git branch
22. new file on branch
    echo "rrepo" > README.md
    git add README.md
    git commit -m "Add README.md in add_readme branch"
23. git checkout main
24. provoke a merge conflict by editing the same file
    git checkout -b edit_sample_file
    echo "Edit in edit_sample_file branch" > sample_code.py
    git add sample_code.py
    git commit -m "Edit sample_code.py in edit_sample_file branch"

25.
    git checkout main
    echo "Edit in main branch" > sample_code.py
    git add sample_code.py
    git commit -m "Edit sample_code.py in main branch"

26. git merge edit_sample_file
27. Edit in edit_sample_file branch
28. git add hello.py
29. git push origin main











