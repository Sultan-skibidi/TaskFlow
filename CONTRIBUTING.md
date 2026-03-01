# Contributing to TaskFlow

Thank you for your interest in contributing to **TaskFlow**! This document provides guidelines for contributing to the project.

---

## 📋 How to Contribute

### 1. Fork & Clone
```bash
git clone https://github.com/Sultan-skibidi/TaskFlow.git
cd TaskFlow
```

### 2. Create a Branch
Always create a new branch for your work:
```bash
git checkout -b feature-your-feature-name
```

**Branch naming convention:**
- `feature-*` for new features (e.g., `feature-dark-mode`)
- `fix-*` for bug fixes (e.g., `fix-task-counter`)
- `docs-*` for documentation changes (e.g., `docs-update-readme`)

### 3. Make Changes
- Write clean, readable code
- Follow existing code style and conventions
- Add comments for complex logic
- Test your changes in multiple browsers

### 4. Commit Guidelines
Write clear, descriptive commit messages:

**Good examples:**
- `Add search functionality with text highlighting`
- `Fix task counter not updating after delete`
- `Update README with installation instructions`

**Bad examples:**
- `update`
- `fix stuff`
- `asdfgh`

### 5. Push & Create PR
```bash
git push -u origin feature-your-feature-name
```
Then create a **Pull Request** on GitHub with:
- A clear title describing your changes
- A description of what you changed and why
- Screenshots if you changed the UI

---

## 🧪 Testing

Before submitting your PR, make sure to:

1. Open `index.html` in your browser
2. Test all existing features still work (add, complete, delete, filter, search)
3. Test your new feature thoroughly
4. Check responsiveness on mobile viewport
5. Verify data persists after page refresh (localStorage)

---

## 📁 Project Structure

```
TaskFlow/
├── index.html     # HTML structure
├── style.css      # All styles and animations
├── script.js      # Application logic
├── README.md      # Project documentation
└── .gitignore     # Git ignore rules
```

---

## 🎨 Code Style

- **HTML**: Use semantic elements, proper indentation (4 spaces)
- **CSS**: Use CSS variables from `:root`, follow BEM-like naming
- **JavaScript**: Use JSDoc comments, `const`/`let` (no `var`), descriptive function names

---

## 👥 Team Members

| NIM | Name | Role |
|---|---|---|
| 001202400200 | Sultan Zhalifunnas Musyaffa | Project Lead & Core Features |
| 001202400069 | Risly Maria Theresia Worung | UI/UX Design |
| 001202400040 | Misha Andalusia | Task Features |
| 001202400054 | Fathir Barhouti Awlya | Search & Storage |

---

Thank you for contributing! 🚀
