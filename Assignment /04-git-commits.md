# Assignment 4 – Repository with at least three meaningful commits

**Name:Pawan Singh Kushwaha
**Roll Number:** 
**Course:** BCAI
**Date:**  22/10/2026

## 1. Aim

To create a Git repository and make at least three meaningful commits using Git and GitHub.

## 2. Requirements

* Visual Studio Code (VS Code)
* Git installed on the computer
* A GitHub account
* Basic knowledge of HTML and CSS

## 3. Procedure

### Step 1: Create a Project

Create a folder named `MyProject` and open it in VS Code.

### Step 2: First Commit — Create README.md

Create a file named `README.md` and write:

```text
# MyProject
This is my first GitHub project.
It contains a simple webpage created using HTML and CSS.
```

Open the VS Code terminal and run:

```bash
git init
git add README.md
git commit -m "Add project README"
```

### Step 3: Second Commit — Create a Webpage

Create a file named `index.html` and add this code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Project</title>
</head>
<body>
    <h1>Welcome to My Project</h1>
    <p>This is my first webpage.</p>
</body>
</html>
```

Save the file and run:

```bash
git add index.html
git commit -m "Create homepage"
```

### Step 4: Third Commit — Add CSS Styling

Create a file named `style.css` and add:

```css
body {
    background-color: lightblue;
    text-align: center;
    font-family: Arial, sans-serif;
}

h1 {
    color: darkblue;
}
```

Add the CSS file to your HTML by inserting the following line inside the `<head>` section of `index.html`:

```html
<link rel="stylesheet" href="style.css">
```

Save the changes and run:

```bash
git add index.html style.css
git commit -m "Add webpage styling"
```

### Step 5: Verify the Commits

Run this command in the VS Code terminal:

```bash
git log --oneline
```

You should see at least three commits.

### Step 6: Upload the Project to GitHub

1. Log in to GitHub and create a new repository named `MyProject`.
2. Copy the repository URL.
3. Run these commands in the VS Code terminal, replacing the example URL with your own:

```bash
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/MyProject.git
git push -u origin main
```

## 4. Result

Successfully created a Git repository, made three meaningful commits, and uploaded the project to GitHub.

## 5. Proof of Completion

Attach the following screenshots to your assignment:

1. The project files visible in VS Code.
2. The output of `git log --oneline`, showing all three commits.
3. Your GitHub repository page showing the uploaded files and commit history.
