Git Large File Storage (LFS) is an extension that allows Git to handle large files efficiently by storing them outside the Git repository. This helps reduce repository size and improve performance when working with large files. Here's how to use Git LFS:

## Installing Git LFS

1. **Download and Install Git LFS:**
   - Download the Git LFS installer for your operating system from https://git-lfs.github.com/.
   - Follow the installation instructions to install Git LFS on your machine.

2. **Initialize Git LFS in Your Repository:**
   - Navigate to your Git repository directory in the terminal.
   - Run the following command to initialize Git LFS:
     ```bash
     git lfs install
     ```

## Tracking Large Files

1. **Specify Large File Types:**
   - Identify the types of files you want to track with Git LFS (e.g., images, videos, binaries).
   - Add file patterns to the `.gitattributes` file to specify which files should be managed by Git LFS. For example:
     ```
     *.jpg filter=lfs diff=lfs merge=lfs -text
     ```

2. **Track Large Files:**
   - Stage large files for tracking with Git LFS using the `git lfs track` command. For example:
     ```bash
     git lfs track '*.jpg'
     ```

3. **Commit Changes:**
   - Commit the changes to the `.gitattributes` file to track large files with Git LFS:
     ```bash
     git add .gitattributes
     git commit -m "Track large files with Git LFS"
     ```

## Pushing and Pulling Large Files

1. **Pushing Changes:**
   - When pushing changes to a remote repository, Git LFS automatically uploads large files to the Git LFS server. Use the regular `git push` command as usual.

2. **Pulling Changes:**
   - When pulling changes from a remote repository, Git LFS automatically downloads large files as needed. Use the regular `git pull` command as usual.

## Additional Git LFS Commands

- **git lfs ls-files:** List the large files tracked by Git LFS.
- **git lfs migrate:** Migrate large files from Git history to Git LFS.
- **git lfs prune:** Remove old versions of large files not needed in the current workspace.

By using Git LFS, teams can efficiently manage and version large files within their Git repositories, improving performance and collaboration.
