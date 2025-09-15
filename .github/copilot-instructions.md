# GitHub Profile Repository

This is a GitHub profile repository (jeremygaither/jeremygaither) that displays a profile README on GitHub. It contains a single README.md file that appears on the owner's GitHub profile page.

**ALWAYS follow these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.**

## Working Effectively

### Repository Structure
- **README.md**: The main profile README file that displays on the GitHub profile
- **.github/**: Contains repository configuration including these instructions
- **No build system**: This repository contains no code to compile, test, or run
- **No dependencies**: No package.json, requirements.txt, or other dependency files
- **No CI/CD**: Only dynamic Copilot workflows exist

### Basic Operations (All operations complete in <1 second)
- View repository status: `git --no-pager status`
- View recent commits: `git --no-pager log --oneline -10`
- Check differences: `git --no-pager diff`
- View current README: `cat README.md`
- View repository structure: `ls -la`

### Making Changes to Profile README
1. **Always backup before making changes**: `cp README.md README.md.backup`
2. **Edit the README.md file directly** using your preferred method
3. **Validate the change**: `cat README.md` to review content
4. **Check git status**: `git --no-pager status`
5. **View your changes**: `git --no-pager diff`
6. **Restore if needed**: `cp README.md.backup README.md && rm README.md.backup`

### Common Profile README Content Types
- **Personal introduction**: Name, role, interests
- **Current activities**: What you're working on, learning
- **Contact information**: How to reach you
- **Skills and technologies**: Programming languages, tools
- **GitHub stats**: Contribution graphs, repository stats
- **Social links**: LinkedIn, Twitter, personal website

## Validation

### Manual Validation Requirements
**CRITICAL**: After making any changes to README.md, you MUST:
1. **View the rendered content**: Use `cat README.md` to ensure formatting is correct
2. **Check for syntax errors**: Ensure Markdown syntax is valid
3. **Verify special characters**: Ensure emojis and Unicode characters display correctly
4. **Test links**: If adding links, verify URL format is correct
5. **Profile preview**: Remember that changes will be visible on the GitHub profile page

### Content Validation Scenarios
**ALWAYS test these scenarios after making README changes:**
- **Basic rendering**: Verify headers, lists, and text format correctly
- **Emoji display**: Ensure emojis (👋, 🔭, 🌱, etc.) appear as intended
- **Comment sections**: Verify HTML comments remain hidden in rendered view
- **Line breaks**: Ensure proper spacing and paragraph formatting
- **Character encoding**: Check for any encoding issues with special characters

## Timing Expectations

All operations in this repository are extremely fast:
- **File operations**: <1 second (cat, ls, cp, mv)
- **Git operations**: <1 second (status, diff, log, add)
- **Content validation**: <1 second (viewing, checking syntax)

**NEVER CANCEL** operations - they complete almost instantly.

## Common Tasks

### Updating Profile Information
1. **Add current work**: Update "🔭 I'm currently working on ..." section
2. **Add learning goals**: Update "🌱 I'm currently learning ..." section  
3. **Add contact info**: Update "📫 How to reach me: ..." section
4. **Add collaboration interests**: Update "👯 I'm looking to collaborate on ..." section

### Adding New Sections
- **Skills section**: Add programming languages, frameworks, tools
- **Statistics**: Add GitHub stats widgets or contribution graphs
- **Projects**: Link to notable repositories or portfolio items
- **Social links**: Add LinkedIn, Twitter, personal website links

### Best Practices for Profile READMEs
- **Keep it concise**: Profile READMEs should be scannable and engaging
- **Use emojis sparingly**: They add personality but shouldn't overwhelm
- **Include current information**: Keep work status and projects up to date
- **Test formatting**: Always verify Markdown renders correctly
- **Professional tone**: Balance personality with professionalism

## Repository Maintenance

### File Management
- **Only edit README.md**: This is the primary content file
- **Preserve .github/ directory**: Contains important repository configuration
- **No cleanup needed**: No build artifacts, dependencies, or temporary files

### Version Control
- **Small, focused commits**: Each change should have a clear purpose
- **Descriptive commit messages**: Explain what profile information was updated
- **Review before committing**: Always check `git diff` before committing changes

## Quick Reference

### Frequently Used Commands
```bash
# View current profile README
cat README.md

# Check what's changed
git --no-pager status
git --no-pager diff

# View repository structure  
ls -la

# View recent changes
git --no-pager log --oneline -5
```

### Repository Contents
```
/home/runner/work/jeremygaither/jeremygaither/
├── README.md              # Profile README (452 bytes)
├── .github/
│   └── copilot-instructions.md
└── .git/                  # Git repository data
```

### Typical README.md Structure
```markdown
## Hi there 👋

<!--
**jeremygaither/jeremygaither** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
```

## Troubleshooting

### Common Issues
- **Content not appearing**: Ensure README.md is in repository root
- **Formatting issues**: Check Markdown syntax with `cat README.md`
- **Missing changes**: Verify file was saved with `git status`
- **Profile not updating**: Changes may take a few minutes to appear on GitHub

### Emergency Recovery
If README.md becomes corrupted:
1. **Check git history**: `git --no-pager log --oneline`
2. **Restore from previous commit**: `git checkout HEAD~1 -- README.md`
3. **Verify restoration**: `cat README.md`