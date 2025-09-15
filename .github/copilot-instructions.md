# GitHub Profile Repository - jeremygaither/jeremygaither

This is Jeremy Gaither's special GitHub profile repository. The README.md file in this repository automatically appears on Jeremy's GitHub profile page (github.com/jeremygaither). This is a simple, content-focused repository with no build processes, dependencies, or complex CI/CD workflows.

**Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.**

## Working Effectively

### Repository Structure
- **Repository Type**: GitHub Profile Repository (special repository that displays on user's GitHub profile)
- **Primary File**: `README.md` - This file appears on Jeremy's GitHub profile
- **No Build Process**: This repository has no compilation, bundling, or build steps
- **No Dependencies**: No package.json, requirements.txt, or dependency management files
- **No CI/CD**: No GitHub Actions workflows or continuous integration
- **Language**: Markdown only

### Essential Commands (All commands complete in under 1 second)
```bash
# Navigate to repository root
cd /home/runner/work/jeremygaither/jeremygaither

# Check repository status
git --no-pager status

# View current README content
cat README.md

# Edit README.md (use your preferred editor)
# File content appears on GitHub profile at github.com/jeremygaither

# Validate changes before committing
git --no-pager diff README.md

# Stage changes
git add README.md

# View staged changes
git --no-pager diff --cached

# Reset/undo changes if needed
git checkout README.md
```

### Markdown Validation
- **No built-in markdown tools available** in the environment (no markdownlint, pandoc, or Python markdown)
- **Validation Strategy**: Preview changes using GitHub's markdown rendering after push
- **GitHub Profile Display**: Changes to README.md appear immediately on github.com/jeremygaither after push

## Validation and Testing

### Manual Validation Requirements
Since this is a profile repository, validation focuses on content and markdown formatting:

1. **Content Review**:
   - Verify README.md contains appropriate profile information
   - Check that markdown syntax is correct
   - Ensure no sensitive information is included

2. **Git Workflow Validation**:
   - `git --no-pager status` - Check working directory status
   - `git --no-pager diff README.md` - Review changes before staging
   - `git --no-pager log --oneline -5` - Verify commit history

3. **Profile Display Validation**:
   - After pushing changes, verify they appear correctly on github.com/jeremygaither
   - Check that markdown renders properly on the GitHub profile page

### Common Validation Commands
```bash
# Check file content and line count
wc -l README.md && file README.md

# View recent commit history with changes
git --no-pager log --stat --oneline -3

# Check for unstaged/staged changes
git --no-pager status --porcelain

# Preview markdown structure (basic check)
head -10 README.md && echo "..." && tail -5 README.md
```

## Working with Profile Content

### Profile README Structure
The current README.md follows GitHub's default profile template:
- Header with greeting
- Commented template with profile ideas
- Standard emoji usage for visual appeal

### Content Guidelines
- **Keep it professional**: This appears on the public GitHub profile
- **Use proper markdown**: Headings, lists, links, and formatting
- **Include contact/social information**: How people can reach Jeremy
- **Highlight current work**: Projects, learning goals, collaboration interests
- **Use emojis sparingly**: For visual appeal but maintain professionalism

### Editing Best Practices
```bash
# Always backup before major changes
cp README.md README.md.backup

# Make incremental changes
# Edit small sections at a time

# Test markdown syntax with basic commands
grep -E "^#{1,6} " README.md  # Check headers
grep -E "^\- " README.md      # Check lists
grep -E "\[.*\].*\(.*\)" README.md  # Check links

# Remove backup after successful changes
rm README.md.backup
```

## Repository Information

### Git Configuration
- **Remote Origin**: https://github.com/jeremygaither/jeremygaither
- **Default Branch**: Varies (check with `git branch -a`)
- **Repository Type**: Public (required for profile display)

### File Inventory
```
/home/runner/work/jeremygaither/jeremygaither/
├── .git/                 # Git repository data
├── .github/              # GitHub configuration (created for copilot-instructions.md)
│   └── copilot-instructions.md  # This file
└── README.md            # Profile content (16 lines, UTF-8 text)
```

### Common Tasks Reference
```bash
# Repository root listing
ls -la
# Output: .git/, .github/, README.md

# File type check
file README.md
# Output: exported SGML document, Unicode text, UTF-8 text

# Quick content check
head -5 README.md
# Output: Shows the profile greeting and start of template

# Git remote verification
git remote -v
# Output: Shows GitHub repository URLs for fetch and push
```

## Key Points for Agents

### What Works
- **Direct editing** of README.md using any text editor
- **Standard git operations** (add, commit, push, diff, status)
- **Immediate content validation** through file commands and git diff
- **Fast operations** - all commands complete in under 1 second

### What Doesn't Apply
- **No build/compile steps** - This is not a code project
- **No dependency management** - No package.json, requirements.txt, etc.
- **No testing framework** - Content validation only
- **No linting tools** - No markdown linters available in environment
- **No CI/CD validation** - No GitHub Actions to verify

### Special Considerations
- **Profile Impact**: Changes directly affect Jeremy's public GitHub profile
- **Public Visibility**: All content is publicly visible on GitHub
- **Immediate Effect**: Pushed changes appear on profile within minutes
- **No Rollback Complexity**: Git revert is straightforward for content changes

### Timing Expectations
- **File operations**: Instantaneous (under 0.01 seconds)
- **Git operations**: Very fast (under 0.01 seconds)  
- **Profile update**: 1-5 minutes after push to appear on GitHub profile

**NEVER CANCEL any operation** - all operations in this repository complete in under 1 second, so timeouts are unnecessary.

## Final Notes

This repository serves a single, focused purpose: displaying Jeremy's professional profile on GitHub. Keep changes simple, professional, and focused on accurately representing Jeremy's current work and interests. The simplicity of this repository is intentional - it's about content, not code complexity.