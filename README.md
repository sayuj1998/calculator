# Git Workshop – Calculator Activity 

Welcome to the Git Workshop! 
In this activity, you’ll practice using Git commands while fixing a simple calculator app.  

## Steps  

### 1. Fork this Repository  
Click the **Fork** button at the top right of this page to create your own copy of this repo.  

### 2. Clone Your Fork  
First, move to a folder where you created git-workshop.
Now clone your forked repo:
```
git clone https://github.com/<your-username>/git-workshop-calculator.git
```

### 3. Move into the folder
```
cd git-workshop-calculator
```

### 4. Create a New Branch
It’s best practice not to work directly on main. Create and switch to a new branch:
```
git switch -c fix-calculator
```

### 5. Open in VS Code
```
code .
```

### 6. Fix the functions
Open calculator.py and fix the code.

### 7. Run the test
Keep fixing functions until all the tests pass.

### 8. Commit Your Changes
```
git add .
git commit -m "Fixed"
git push origin fix-calculator
```
