# DevOps Git Project

## 📌 Objective

This project demonstrates the use of Git best practices for managing a DevOps project. It includes proper version control, branching strategy, pull requests, and documentation using Git and GitHub.

---

## 🛠️ Tools Used

* Git
* GitHub

---

## 📁 Project Structure

```
devops-git-project/
│
├── app.js
├── README.md
└── .gitignore
```

---

## 🚀 Features Implemented

* Git repository initialization
* Branching strategy (main, dev, feature)
* Feature development using separate branch
* Pull request workflow
* Merging changes safely
* Version tagging
* Project documentation

---

## 🌿 Branching Strategy

The project follows a structured branching model:

* **main** → Production-ready code
* **dev** → Development branch
* **feature/login** → Feature-specific development

### Workflow:

```
feature/login → dev → main
```

---

## 🔁 Git Workflow Steps

### 1. Initialize Repository

```
git init
```

### 2. Create and Switch Branches

```
git checkout -b dev
git checkout -b feature/login
```

### 3. Add and Commit Changes

```
git add .
git commit -m "Added login feature"
```

### 4. Push Branches to GitHub

```
git push origin main
git push origin dev
git push origin feature/login
```

### 5. Pull Requests

* Created PR: **feature/login → dev**
* Created PR: **dev → main**

### 6. Merge Changes

* Merged feature branch into dev
* Merged dev branch into main

### 7. Version Tagging

```
git tag v1.0
git push origin v1.0
```

---

## 📄 Sample Code

### app.js

```js
console.log("DevOps Git Project Started");
console.log("Login feature added");
```

---

## 🚫 .gitignore

```
node_modules/
.env
*.log
```

---

## 📸 Screenshots (To be included)

* Git initialization
* Project structure
* Branch creation
* Commit history
* Pull request creation
* Merge confirmation
* Final repository view
* Version tag

---

## 🎯 Outcome

This project successfully demonstrates:

* Proper use of Git for version control
* Implementation of branching strategy
* Safe code integration using pull requests
* Maintaining clean and structured repository

---

## 📌 Conclusion

Using Git and GitHub, this project follows industry-standard practices for managing code changes in a collaborative DevOps environment. It highlights the importance of structured workflows, version control, and documentation.

---
