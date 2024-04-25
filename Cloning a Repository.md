Cloning a repository allows you to create a local copy of the repository on your machine. This is essential for working on projects collaboratively or contributing to open-source projects. Follow the steps below to clone a repository: 
## Using HTTPS 

1. **Copy Repository URL:** 
   - Go to the repository on GitHub. 
   - Click on the "Code" button. 
   - Copy the HTTPS URL. 
2. **Open Terminal:** Navigate to the directory where you want to clone the repository.   
3. **Clone the Repository:** ```git clone <repository_url>```
	Replace `<repository_url>` with the URL you copied earlier.
4. **Authenticate (if prompted):**    
    - If the repository is private, you may be prompted to enter your GitHub username and password.
5. **Verify Clone:**    
    - After cloning, you'll have a local copy of the repository in the specified directory.

## Using SSH (Optional)

If you've set up SSH keys for GitHub authentication, you can use SSH instead of HTTPS for cloning. Here's how:
1. **Copy SSH URL:**    
    - Go to the repository on GitHub.
    - Click on the "Code" button.
    - Copy the SSH URL.
2. **Open Terminal:**    
    - Navigate to the directory where you want to clone the repository.
3. **Clone the Repository using SSH:** `git clone <ssh_repository_url>`
	Replace `<ssh_repository_url>` with the SSH URL you copied earlier.    
4. **Verify Clone:**  After cloning, you'll have a local copy of the repository in the specified directory.
