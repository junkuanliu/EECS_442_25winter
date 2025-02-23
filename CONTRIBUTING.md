# Contributing to EECS 442 Notes 📚

Thank you for your interest in contributing to the EECS 442 lecture notes repository! This repository is designed for students to collaboratively share and maintain notes for the **EECS 442: Computer Vision** course at the University of Michigan. Below are the guidelines for contributing to this repository.

---

## 📌 Contribution Guidelines

### 🛠 How to Contribute
1. **Fork the repository**  
   Click on the "Fork" button in the top right corner of this page to create your own copy of the repository.

2. **Clone your fork**  
   Clone your fork to your local machine:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/EECS442-Notes.git
   cd EECS442-Notes
   ```
3. **Create a new branch**
   ```bash
   git checkout -b add-notes-weekX
   ```
4. **Add your notes**。
Place your lecture notes in the correct directory inside notes/.  
File formats: PDF (.pdf) or Markdown (.md)  
**Naming convention:**  
PDF: lectureX_notes_yourname.pdf  
Markdown: lectureX_notes_yourname.md  
Example:  
```bash
EECS442-Notes/
├── notes/
│   ├── Week1/
│   │   ├── lecture1_notes.pdf
│   │   ├── lecture1_summary.md
│   ├── Week2/
│   │   ├── lecture2_notes.pdf
│   │   ├── lecture2_summary.md
```

6. **Commit your changes**
   ```bash
   git add .
   git commit -m "Added notes for Week X - Lecture Y"
   ```
7. Push the branch to your fork
  ```bash
  git push origin add-notes-weekX
  ```
7. Submit a Pull Request (PR)
Go to your forked repository on GitHub.
Click on "New Pull Request."
Select your branch and submit the PR.
Use the following title format: [Week X] Lecture Y Notes
Fill out the PR template to describe your changes.
