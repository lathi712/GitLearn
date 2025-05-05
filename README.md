# GitLearn

A repository dedicated to learning and practicing Git commands and workflows. This repo serves as both a learning resource and a playground for Git experimentation.

## Contents

- Basic Git commands and usage examples
- Branching and merging strategies
- Collaboration workflows
- Git best practices

## Git Commands Quick Reference

### Basic Commands

```bash
# Initialize a repository
git init

# Check status of working directory
git status

# Add files to staging area
git add <filename>
git add .  # Add all files

# Commit changes
git commit -m "Your commit message"

# View commit history
git log
git log --oneline  # Compact view
```

### Branching and Merging

```bash
# Create and switch to a new branch
git checkout -b <branch-name>

# Switch between branches
git checkout <branch-name>

# List all branches
git branch

# Merge branches
git merge <branch-name>
```

### Remote Repositories

```bash
# Clone a repository
git clone <repository-url>

# Add a remote repository
git remote add origin <remote-repository-url>

# Push changes to remote
git push origin <branch-name>

# Pull changes from remote
git pull origin <branch-name>
```

## Git Workflows

### Feature Branch Workflow

1. Create a feature branch from main
2. Make changes and commit to the feature branch
3. Push the feature branch to the remote repository
4. Create a pull request
5. After review, merge the feature branch into main

### Git Flow

A more structured workflow with dedicated branches:
- `main` - Production code
- `develop` - Integration branch
- `feature/*` - New features
- `release/*` - Release preparation
- `hotfix/*` - Emergency fixes for production

## Learning Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)

## License

MIT

---

Feel free to use this repository to practice Git commands and workflows!