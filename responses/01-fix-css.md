---

## Step 1: Fix the CSS Bug 🐛

### 🎯 Your Mission

Fix the CSS stylesheet link in `index.html` so the World Clock displays with proper styling.

### 🔍 The Problem

The file `index.html` has a typo on line 7:
```html
<link rel="stylesheet" href="styls.css">
```

It should be:
```html
<link rel="stylesheet" href="styles.css">
```

### 📋 Instructions

1. **Create a new branch** for your fix:
   ```bash
   git checkout -b fix-css-link
   ```

2. **Open `index.html`** and fix the typo on line 7

3. **Save, commit, and push**:
   ```bash
   git add index.html
   git commit -m "Fix CSS stylesheet link typo"
   git push -u origin fix-css-link
   ```

### ✅ Success Criteria

- CSS link changed from `styls.css` to `styles.css`
- Changes committed and pushed to a branch

---

💡 **Tip**: You can also ask GitHub Copilot for help: "Can you fix the CSS link in index.html?"
