---

## Step 2: Create a Pull Request with MCP 🔀

### 🎯 Your Mission

Use **GitHub Copilot with MCP tools** to create a professional Pull Request that links to an issue.

### 🧠 Learning Focus

This step teaches you how to:
- Use Copilot to create GitHub issues via MCP
- Create Pull Requests directly from VS Code
- Link PRs to issues for automatic tracking

### 📋 Instructions

**Part 1: Create a GitHub Issue (Optional)**

If you want to practice the full workflow, ask Copilot:
```
Can you create a GitHub issue to track this CSS bug? Title it "Fix CSS stylesheet link typo" and describe the problem - that the CSS file reference in index.html had a typo (styls.css instead of styles.css).
```

**Expected:** Copilot will use `mcp_github_issue_write` to create the issue and give you the issue number.

---

**Part 2: Create a Pull Request**

Ask Copilot:
```
Can you create a pull request from this branch to main? Title it "Fix CSS stylesheet link typo" and include "Fixes #X" in the description where X is the issue number.
```

*(Replace X with the issue number from Part 1, or use any existing issue)*

**Expected:** Copilot will use `mcp_github_create_pull_request` to create the PR with proper issue linking.

---

### ✅ Success Criteria

- Created a GitHub issue using Copilot + MCP (optional)
- Created a PR using Copilot + MCP
- PR description includes `Fixes #<issue-number>` for automatic linking
- PR targets the `main` branch

---

💡 **Key Learning**: You're using MCP tools seamlessly from VS Code without leaving your editor - this is the power of integrated AI workflows!
