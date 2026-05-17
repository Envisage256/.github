# Contribution Guidelines
This document defines how contributors work within Envisage repositories.  
It establishes a consistent workflow for collaboration, code quality, and project management.

All contributors are expected to follow these guidelines when working on any Envisage project.

## Purpose of These Guidelines
These guidelines exist to:
- Ensure consistency across all repositories
- Maintain code quality and readability
- Streamline collaboration between contributors
- Prevent conflicts and mismanagement of code
- Support scalable development as the organization grows

## Working with Repositories
### 1. Cloning a Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/envisage256/<repository-name>.git 
```

### 2. Navigate into the project directory:
```bash
cd <repository-name>
```

### 3. Keeping Your Local Repository Updated
Always sync with the main branch before starting work:

```bash
git checkout main
git pull origin main
```

## Branching Strategy 
All work must be done on separate branches. Direct commits to main are not allowed.

### Branch Naming Convention 
Use clear, descriptive names: 
- feature/<feature-name>
- fix/<issue-name>
- docs/<documentation-update>
- refactor/<component-name> 

Examples:
- feature/login-system
- fix/navbar-overflow
- docs/readme-update

## Commits 
### 1. Commit Message Format
Use structured, meaningful commit messages: 

> **type: short description** 

Types include: 
- feat — new feature
- fix — bug fix
- docs — documentation changes
- refactor — code restructuring
- style — formatting or UI changes
- test — testing updates

Examples: 
- feat: add student search functionality
- fix: resolve mobile navigation issue
- docs: update installation instructions

### 2. Commit Best Practices
- Keep commits small and focused
- Write clear and descriptive messages
- Avoid committing unnecessary files (e.g., node_modules, temporary files) 

## Pull Requests 
### 1. Before Submitting a Pull Request 
Ensure that: 
- Your code is functional and tested
- There are no console errors
- The UI is responsive (if applicable)
- You have pulled the latest changes from main

### 2. Creating a Pull Request 
Push your branch: 

```bash
git push origin <branch-name>
```

Open a Pull Request on GitHub and provide a clear description including;
- What was implemented or fixed
- Why the change was necessary
- Screenshots (for UI changes)

### 3. Pull Request Requirements
- Must be reviewed before merging
- Must not introduce breaking changes
- Must follow coding standards
- Must be linked to an issue (if applicable)

## Code Reviews 
Code reviews are mandatory for maintaining quality.

### 1. Review Expectations
Reviewers should:
- Check code correctness and functionality
- Ensure adherence to coding standards
- Suggest improvements where necessary
- Identify potential bugs or inefficiencies 

### 2. Contributor Responsibilities
- Respond to feedback constructively
- Make requested changes promptly 

**Do not merge your own pull request without approval**

## Issue Management
All tasks should be tracked using GitHub Issues.

### 1. Creating Issues
Include:
- Clear title
- Detailed description
- Steps to reproduce (for bugs)
- Expected vs actual behavior

### 2. Issue Types
- Bug reports
- Feature requests
- Enhancements
- Tasks

## Collaboration Workflow
The standard workflow is:
1. Create or pick an issue
2. Create a branch
3. Implement the solution
4. Commit changes
5. Open a pull request
6. Undergo review
7. Merge into main

## General Rules
- Do not push directly to main
- Do not overwrite others' work
- Communicate clearly when working on shared features
- Keep code clean and maintainable
- Follow all documented standards 

## Final Notice 

These guidelines are designed to keep Envisage projects organized, scalable, and professional. 

As the organization evolves, these practices may be refined. 

All contributors are expected to stay aligned with these standards. 
