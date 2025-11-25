# 🎓 GitHub MCP Workflow - Interactive Learning Exercise

<div align="center">

![GitHub MCP](https://img.shields.io/badge/GitHub-MCP-blue?style=for-the-badge&logo=github)
![Interactive](https://img.shields.io/badge/Type-Interactive-green?style=for-the-badge)
![Skill Level](https://img.shields.io/badge/Level-Beginner-brightgreen?style=for-the-badge)

**Learn GitHub workflows with AI assistance through hands-on practice!**

</div>

---

## 👋 Welcome!

This is an **interactive learning exercise** inspired by [GitHub Skills](https://skills.github.com/). You'll learn how to use **GitHub MCP (Model Context Protocol)** with **VS Code Copilot** to streamline your development workflow - all through guided, hands-on practice!

### 🎯 What You'll Build

You'll fix a broken World Clock web application by working through a complete DevOps workflow:
- 🔍 Investigate bugs with AI assistance
- 📝 Create and track issues using MCP tools
- 🌿 Implement professional branching strategies
- 🔀 Create and merge Pull Requests
- ✅ Complete the full development lifecycle

### ⏱️ Time Commitment

**15-30 minutes** - Perfect for a focused learning session!

---

## � What You'll Learn

By completing this exercise, you'll gain practical experience with:

- ✅ **GitHub MCP Integration** - Use MCP tools directly in VS Code
- ✅ **AI-Assisted Debugging** - Let Copilot help find and fix bugs
- ✅ **Issue Management** - Create and track bugs professionally
- ✅ **Git Branching** - Implement proper hotfix workflows
- ✅ **Pull Requests** - Create PRs with proper issue linking
- ✅ **DevOps Best Practices** - Complete development lifecycle

### 🎓 Prerequisites

Before starting, make sure you have:
- **VS Code** installed on your computer
- **GitHub Copilot** extension activated
- **GitHub MCP Server** configured (we'll verify this together!)
- **Basic Git knowledge** (commit, push, branch)
- A **GitHub account**

---

## 🚀 How to Start This Exercise

### Step 1: Fork This Repository

Click the **Fork** button at the top of this page to create your own copy of this exercise.

### Step 2: Clone to Your Computer

```bash
git clone https://github.com/YOUR-USERNAME/github-mcp-demo.git
cd github-mcp-demo
```

### Step 3: Open in VS Code

```bash
code .
```

### Step 4: Start the GitHub MCP Server

1. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
2. Search for `MCP: Show Installed Server`
3. Find **github** in the list
4. Right-click and select **Start Server**
5. Verify it shows "Connected" or "Running"

**Need help setting up MCP?** Check out:
- [GitHub MCP Server Documentation](https://github.com/github/github-mcp-server)
- [Copilot MCP Integration Guide](https://docs.github.com/en/copilot/how-tos/provide-context/use-mcp/extend-copilot-chat-with-mcp)

### Step 5: Trigger the Welcome Issue

Push a commit to your forked repository or manually trigger the welcome workflow:

```bash
git commit --allow-empty -m "Start exercise"
git push
```

**That's it!** The automated bot will create your first issue with instructions. Just follow along! 🎉

---

## 🎮 How the Exercise Works

This is an **automated, bot-driven exercise** similar to GitHub Skills courses:

1. 🤖 **The Bot Guides You** - Issues are created automatically with step-by-step instructions
2. ✅ **Automated Validation** - Your work is checked automatically when you push code
3. 📝 **Instant Feedback** - Get immediate comments on whether you're on track
4. 📈 **Progressive Learning** - Each step builds on the previous one

### Exercise Flow

```
📝 Welcome Issue → 🐛 Fix CSS Bug → 🔀 Create PR → 🎉 Merge & Complete
```

---

## 🐛 The Challenge

The World Clock application has a **critical styling bug**:

- **Problem**: CSS stylesheet isn't loading
- **Cause**: Typo in the HTML file (`styls.css` instead of `styles.css`)
- **Impact**: Page displays without any styling
- **Your Mission**: Find and fix it using GitHub MCP tools!

---

## 💡 Tips for Success

- 💬 **Ask Copilot for help** - That's what this exercise is about!
- 📖 **Read the issue instructions carefully** - Each step has specific requirements
- ✅ **Wait for validation** - The bot checks your work automatically
- 🔄 **Push your changes** - Workflows trigger on push events
- 🙋 **Get stuck?** Check the response templates in the `responses/` folder

---

## 🏗️ Project Structure

```
github-mcp-demo/
├── .github/
│   ├── workflows/          # Automated exercise workflows
│   │   ├── 0-welcome.yml   # Creates welcome issue
│   │   ├── 1-fix-css.yml   # Validates CSS fix
│   │   └── 2-check-pr.yml  # Validates PR creation
│   └── copilot-instructions.md
├── responses/              # Bot response templates
│   ├── 00-welcome.md
│   ├── 01-success-css-fixed.md
│   ├── 01-error-css-not-fixed.md
│   ├── 02-create-pr.md
│   ├── 02-success-pr-created.md
│   └── 03-merge-pr.md
├── index.html              # World Clock app (has the bug!)
├── styles.css              # CSS styling
├── script.js               # JavaScript logic
└── README.md               # You are here!
```

---

## 🔧 Troubleshooting

### MCP Server Won't Start
- Ensure `.vscode/mcp.json` exists in the project
- Restart VS Code
- Check that GitHub Copilot is authenticated

### Welcome Issue Not Created
- Try manually triggering: Actions → Step 0 - Welcome → Run workflow
- Check that Actions are enabled in your repository settings

### Bot Not Responding
- Make sure you're pushing to the correct branch
- Check the Actions tab for workflow runs
- Verify your changes match the validation criteria

---

## 🌟 What's Next?

After completing this exercise, level up your skills:

### 🤖 [GitHub Coding Agent Demo](https://github.com/david-pizzi-cg/github-coding-agent-demo)
Learn autonomous AI workflows where the coding agent works independently on assigned issues.

### 🛡️ [GitHub Copilot Instructions Demo](https://github.com/david-pizzi-cg/github-copilot-instructions-demo)
Add safeguards and quality gates to AI-assisted development.

---

## 📖 Additional Resources

- 📚 [GitHub MCP Server Documentation](https://github.com/github/github-mcp-server)
- 🤖 [VS Code Copilot Integration](https://code.visualstudio.com/docs/copilot)
- 🎓 [GitHub Skills Courses](https://skills.github.com/)
- 🔧 [DevOps Best Practices](https://docs.github.com/en/actions/guides)

---

## 🤝 Contributing

Found a bug or have suggestions? Feel free to open an issue or submit a PR!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Ready to start your AI-assisted development journey?** 🚀

Fork this repo and let's go! 

Made with ❤️ for developers learning AI workflows

</div>