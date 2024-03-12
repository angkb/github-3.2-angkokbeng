# github-3.2-angkokbeng

Explain what is GitHub Authentication and how what methods available to be implemented?

GitHub authentication is the process of verifying the identity of users accessing GitHub services, ensuring that only authorized individuals or systems can interact with repositories, issues, pull requests, and other GitHub features. GitHub supports various authentication methods to secure user accounts and control access to repositories. Here are some of the common authentication methods available on GitHub:

1. **Username and Password:** The traditional method involves users providing their GitHub username and password to log in. However, this method is less secure and is not recommended for automation or third-party applications due to the potential risk of exposing credentials.

2. **Personal Access Tokens (PATs):** Personal Access Tokens are an alternative to passwords for authentication. Users can generate PATs with specific scopes and permissions, allowing them to access GitHub repositories and perform actions on behalf of the account. PATs are often used for automation, scripts, or third-party applications.

3. **OAuth (Open Authorization):** OAuth is a secure and widely-used authorization framework that allows users to grant third-party applications limited access to their resources on GitHub without sharing their credentials. GitHub supports OAuth 2.0, enabling developers to integrate their applications with GitHub's authentication system.

4. **SSH Keys:** Secure Shell (SSH) keys can be used for authentication when interacting with GitHub repositories over the SSH protocol. Users can generate an SSH key pair and add the public key to their GitHub account. This method is commonly used for secure communication between a user's local machine and GitHub.

5. **GitHub App Installation Tokens:** GitHub Apps can be installed on repositories or organizations and can generate installation tokens to authenticate requests to the GitHub API on behalf of the app's installation. These tokens are a secure way to perform automated actions on repositories.

6. **GitHub Actions Tokens:** GitHub Actions, a CI/CD service provided by GitHub, uses tokens for authentication. These tokens are automatically generated and can be used in workflows to authenticate and interact with GitHub repositories during automated build and deployment processes.

When choosing an authentication method for your application or workflow, consider factors such as security, permissions required, and the type of interaction (user-driven or automated). It's essential to follow best practices, such as avoiding the use of plain passwords and regularly rotating access tokens, to enhance the security of your GitHub interactions.

# 15 github commands and what are the usage of them?

1	git config --global user.name : configure author name
2	git config --global user.email : configure the author email address
3	git init : initialize a local Git repository
4	git clone : create a local copy of a remote repository
5	git status : check status
6	git add . :  add all new and changed files to staging area
7	git commit -m "message>" : commit changes
8	git push : push changes to remote repository
9	git push --all : push changes to remote repository all branch
10	git push origin <branch name> : push a branch to your remote repository
11	git pull : update local repository to the newest commit
12	git branch : list branches (the asterisk denotes the current branch)	
13	git branch <branch name> : create a new branch
14	git checkout <branch name> : switch to a branch	
15	git merge <source branch> <target branch> : merge a branch into a target branch

