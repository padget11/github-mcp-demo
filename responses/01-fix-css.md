---

## Step 1: Investigate and Fix the CSS Bug �

### 🎯 Your Mission

Use **GitHub Copilot with MCP** to investigate why the World Clock styling is broken and fix it.

### 🧠 Learning Focus

This step teaches you how to:
- Prompt Copilot to investigate styling issues
- Use AI to identify file linking problems
- Create branches and fix bugs with Copilot assistance

### 📋 Instructions

**Part 1: Investigation with Copilot**

Open Copilot Chat and ask:
```
Copilot, I just opened my World Clock website and it looks completely broken - all the beautiful styling is missing and it's just plain HTML. Can you investigate what's wrong with the styling?
```

**Expected:** Copilot will analyze `index.html` and identify the typo in the CSS link on line 7.

---

**Part 2: Create Hotfix Branch**

Ask Copilot:
```
Perfect! Now let's create a hotfix branch to fix this CSS issue. Can you create a branch called 'hotfix/css-stylesheet-typo' and switch to it?
```

**Expected:** Copilot will create and switch to the new branch.

---

**Part 3: Fix the Bug**

Ask Copilot:
```
Now let's fix the actual bug. Can you correct the CSS link in index.html from 'styls.css' to 'styles.css'? Please show me the change you're making.
```

**Expected:** Copilot will fix the typo and show you the change.

---

**Part 4: Commit and Push**

Ask Copilot:
```
Great! Now let's commit this change and push it to the remote repository.
```

**Expected:** Copilot will commit and push your changes.

### ✅ Success Criteria

- Used Copilot to investigate the styling issue
- Created a hotfix branch with Copilot's help
- Fixed the CSS link from `styls.css` to `styles.css`
- Committed and pushed changes to the branch

---

💡 **Key Learning**: You're directing Copilot step-by-step through a professional workflow - this is "AI as a tool" where you maintain control!
