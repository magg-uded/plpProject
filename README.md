## PLP Git project set up steps

# Local repo set up
1. Create a new folder >> mkdir projectFoody 
2. Initialize a Git repo in the local folder >> git init 
4. Create empty README.md file >> touch README.md
5. Stage README.md file >> git add README.md
6. Open README.md file on VSCode to write on it >> code .
7. Connect local and remote repos >> git remote add origin git@github.com:magg-uded/plpProject.git
8. Commit README.md file to remote repo >> git commit -m "create Readme.md"
9. Push README.md commit >> git push README.md

# Create file in local repo 
1. Create an empty file >> touch xx.txt
2. Add content to file > echo 'xx!' >xx.txt
3. Output content of file >> cat xx.txt

# Stage, commit and push file changes to remote repo
1. Stage changes >> git add hello.txt
2. Commit changes >> git commit -m "Add xx.txt with a greeting"
3. git push -u origin main

# Verify commits on GitHub.com
1. Visit website and confirm "xx.txt" and commit message exist