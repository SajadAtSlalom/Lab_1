# Contributing to Lab_1

Thank you for contributing to this student work sharing repository! This guide will help you submit your work properly.

## 📋 Contribution Process

### 1. Set Up Your Environment

```bash
# Clone the repository
git clone https://github.com/SajadAtSlalom/Lab_1.git
cd Lab_1

# Create a new branch for your work (optional but recommended)
git checkout -b your-name-lab-submission
```

### 2. Create Your Personal Folder

Navigate to the `students/` directory and create a folder with your name:

```bash
cd students
mkdir your_name  # Use your actual name or student ID (e.g., john_doe)
cd your_name
```

### 3. Add Your Work

- Place all your lab files in your personal folder
- Organize your work into subdirectories if needed (e.g., `assignment1/`, `assignment2/`)
- Include a README.md in your folder describing your work

### 4. Commit Your Changes

```bash
# Add your files
git add .

# Commit with a descriptive message
git commit -m "Add [Your Name]'s Lab 1 submission"
```

### 5. Push Your Changes

```bash
# Push to the repository
git push origin your-branch-name
```

### 6. Create a Pull Request (if applicable)

If you're working with a forked repository or need review:
1. Go to the repository on GitHub
2. Click "New Pull Request"
3. Select your branch
4. Add a description of your work
5. Submit the pull request

## 📝 Best Practices

### File Organization

```
students/
└── your_name/
    ├── README.md                 # Description of your work
    ├── assignment1/
    │   ├── code.py
    │   └── documentation.md
    └── assignment2/
        └── project/
```

### Naming Conventions

- **Folder names**: Use lowercase with underscores (e.g., `john_doe`)
- **File names**: Use descriptive, lowercase names (e.g., `bubble_sort.py`, `web_scraper.js`)
- **Branch names**: Use descriptive names (e.g., `john-assignment1`, `jane-lab2-submission`)

### Commit Messages

Write clear commit messages:
- ✅ Good: "Add bubble sort implementation for Assignment 1"
- ✅ Good: "Fix bug in calculator.py"
- ❌ Bad: "Update"
- ❌ Bad: "asdf"

### Code Quality

- **Comment your code**: Explain complex logic
- **Use proper formatting**: Follow language-specific style guides
- **Test your code**: Make sure it runs without errors
- **Include documentation**: Add a README for each assignment

## 🚫 What NOT to Do

- ❌ Don't modify other students' folders
- ❌ Don't commit sensitive information (passwords, API keys, personal data)
- ❌ Don't upload large binary files unless necessary
- ❌ Don't plagiarize or copy code without attribution
- ❌ Don't commit temporary files (`.DS_Store`, `*.pyc`, `node_modules/`, etc.)

## 📁 .gitignore

The repository includes a `.gitignore` file that excludes common temporary files. If you need to add more exclusions, update the `.gitignore` file in the root directory.

## 🆘 Getting Help

If you encounter issues:

1. **Check existing issues**: Someone may have had the same problem
2. **Review documentation**: Read this guide and the main README
3. **Ask for help**: Open an issue or contact your instructor
4. **Be specific**: Include error messages and what you've tried

## 🎓 Academic Integrity

- Share your work for learning purposes
- Give credit when using code from other sources
- Don't directly copy other students' work
- Follow your institution's academic integrity policies

## ✅ Checklist Before Submitting

- [ ] Created personal folder in `students/` directory
- [ ] Added README.md describing my work
- [ ] Code is properly commented
- [ ] Tested code runs without errors
- [ ] No sensitive information in commits
- [ ] Meaningful commit messages
- [ ] Followed naming conventions
- [ ] No unnecessary files committed

Thank you for contributing to Lab_1! Happy coding! 🚀
