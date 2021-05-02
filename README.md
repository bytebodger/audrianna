# audrianna

The personal site for Audrianna.

## Instructions

1. Download and install Git. It's a free tool that pushes your code into the repository (amongst other things).
1. Once Git is installed, create a new directory on the laptop. You can call it whatever you want, but I'll assume in these instructions that the directory is called "code".
1. Open a command prompt (the black terminal application that you use to type in commands on the command line).
1. Navigate to the new directory. You can do this by typing in `cd C:\code`.
1. Once you're _in_ the new directory, type this command: `git clone https://github.com/bytebodger/audrianna.git`. That will bring a local copy of the site down to your laptop. It will also create a "link" between the local code and the remote repository.
1. Under your `C:\code` directory, you should now have a directory called "audrianna".
1. Open Atom and expand the "Open a Project" panel on the right.
1. Click the "Open a Project" button.
1. A Windows File Explorer window will open.
1. Navigate to `C:\code` and then select the "audrianna" folder in it.
1. The files for your site will be shown on the left.  Open the `index.html` file and make some sort of change to it and save the file.
1. In the bottom-right corner, you'll see information about the repository.  This includes the branch name ("main") and buttons for Fetch, GitHub, and Git.
1. Click the GitHub button.  
1. A panel will display on the right, with a Login button.  Click that button.
1. It will then prompt you for a token.  It shows a link to github.atom.io/login.  Click on that link.
1. It will then show you a GitHub screen where you can authorize Atom to work with GitHub.  The default options should be fine.  Click "Authorize atom".
1. It then shows you a GitHub token.  Click "Copy token" to put the token in your clipboard.
1. Back in Atom, paste that token into the "Enter your token..." field, then click "Login".
1. Click the "Git" button in the bottom-right corner of Atom.
1. Under "Unstaged Changes", you should see "index.html", because you have made changes to the file that have not yet been committed to the repository.
