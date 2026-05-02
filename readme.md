# 🚀 Node.js Boilerplate

> Production-ready Node.js project starter with ESLint, Prettier, EditorConfig, and Husky pre-configured.

---

## ✨ What's Included

| Tool             | Purpose                                        |
| ---------------- | ---------------------------------------------- |
| **ESLint**       | Code quality — catches bugs and bad patterns   |
| **Prettier**     | Auto-formatting — consistent code style        |
| **EditorConfig** | Same editor settings across all editors        |
| **Husky**        | Pre-commit hooks — bad code can't be committed |
| **lint-staged**  | Runs linting only on changed files             |

---

## 🚀 Quick Start

```bash
# Clone this boilerplate
git clone https://github.com/tagda-coder/node-boilerplate.git my-project

# Go into the project
cd my-project

# Install dependencies
npm install

# Start coding!
```

---

## 📁 Folder Structure

```
node-boilerplate/
├── .husky/
│   └── pre-commit        # Runs lint-staged before every commit
├── .vscode/
│   ├── settings.json     # Auto format on save
│   └── extensions.json   # Recommended extensions
├── src/                  # Your code goes here
├── .editorconfig         # Editor settings
├── .eslintrc.json        # ESLint rules
├── .gitignore            # Git ignore
├── .prettierignore       # Prettier ignore
├── .prettierrc           # Prettier config
└── package.json          # Scripts + lint-staged config
```

---

## 📝 Available Scripts

```bash
npm run lint          # Check ESLint errors
npm run lint:fix      # Auto-fix ESLint errors
npm run format        # Format all files with Prettier
npm run format:check  # Check formatting without fixing
```

---

## ⚙️ How It Works

**On Save** — Prettier auto-formats your code.

**On Commit** — Husky runs lint-staged automatically:
```
git commit
    ↓
Husky fires pre-commit hook
    ↓
lint-staged runs ESLint + Prettier on changed files
    ↓
Errors? → Commit BLOCKED ❌
All good? → Commit SUCCESS ✅
```

---

## 🔌 Recommended VS Code Extensions

Install these for the best experience:
- **ESLint** — `dbaeumer.vscode-eslint`
- **Prettier** — `esbenp.prettier-vscode`
- **EditorConfig** — `EditorConfig.EditorConfig`
- **Path Intellisense** — `christian-kohler.path-intellisense`

> VS Code will automatically suggest these when you open the project.

---

## 👤 Author

**Mandeep Malakar** — [GitHub](https://github.com/tagda-coder/)

---

> ⭐ Star this repo if it helped you!