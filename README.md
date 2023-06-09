# github-3.2-liau

_SCTP Cloud Infrastructure Module 3.2 Assignment_

## What is GitHib Authentication?
GitHub authentication refers to the process of verifying the identity of users who want to access GitHub. GitHub provides various authentication methods to ensure that only authorized users can perform actions such as pushing changes to repositories, creating issues, or managing settings.

## Common GitHub Authentication Methods:

- Username and password: This is the most basic form of authentication, where users provide their GitHub username and password to login to their GitHub account.

-  Two-Factor Authentication (2FA): GitHub supports 2FA, which adds an extra layer of security by requiring users to provide a second form of authentication, such as a time-based one-time password (TOTP) generated by a mobile app or a physical security key.

- OAuth: GitHub allows users to authenticate using OAuth, which is an open standard for authorization. OAuth enables users to grant third-party applications limited access to their GitHub account without sharing their username and password.

- Personal Access Tokens (PATs): GitHub allows users to generate PATs, which are tokens that can be used as an alternative to passwords for authentication. PATs can be used in place of passwords when accessing the GitHub API or when performing Git operations over HTTPS.

- SSH Keys: GitHub supports authentication using SSH keys, which are cryptographic keys that allow users to securely authenticate with their GitHub account without providing their username and password for every interaction.

- SAML Single Sign-On (SSO): GitHub supports SAML SSO, which allows users to authenticate using their organization's identity provider (IdP) credentials, such as LDAP or Active Directory, to provide a single sign-on experience across multiple services.

## Github Commands Learned In This Module
| Command | Usage |
|---------|-------|
| git clone | Clone a repository into a new directory |
| git add | Adds new or changed files in your working directory to the Git staging area |
| git commit | Creates a commit, which is like a snapshot of your repository |
| git push | Uploads all local branch commits to the corresponding remote branch |
| git pull | Updates your current local working branch, and all of the remote tracking branches |
| git branch | Shows the existing branches in your local repository |
| git branch [branch name] | Create a branch from your current location |
| git checkout | Switches to the specified branch and updates the working directory |

## 4 Github Commands That Will Be Used Most
- **_git clone_**: git clone is often the first command used when starting a new project or when joining an existing team.

- **_git add_**: git add is often used after making changes to files in the repository to stage those changes for a commit.

- **_git commit_**: git commit is a crucial command in Git for recording the history of changes in a project and creating a point of reference for future work.

- **_git push_**: git push is often used after committing changes locally to push those changes to the remote repository so that others can access and review them.