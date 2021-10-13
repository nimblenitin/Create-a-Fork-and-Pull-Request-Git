# Create-a-Fork-and-Pull-Request-Git

Steps-

```

1. Creating a Fork
- Log in to your Github account
- From your browser navigate to the following  repository https://github.com/GithubResources1/Source-repository.git
- In the top-right corner of the page, click Fork button

2. Cloning your Fork
- On GitHub, click on the code button on your repository
- Copy the URL from under Clone with HTTPS option
- Type the following command on your terminal:
$ git clone [the copied HTTPS URL]

3. Syncing fork with the original repository
- Navigate to the directory where the fork has been cloned using the following command in the terminal:
$ cd Source-repository
- Use the following command to see the configured remote repository for your fork:
$ git remote -v
- Use git remote add upstream command, and paste the URL you copied in Step 2 as shown below:
$ git remote add upstream [the copied HTTPS URL]
- Use the following command to verify the new upstream repository you have specified for your fork:
$ git remote -v

4. Pushing your Changes
- Use the git push command to upload your changes to your remote fork on GitHub:
$ git push

5. Creating a Pull Request
- On the GitHub page of your remote fork, click the pull request button 
- Wait for the owner to merge or comment on your changes
- If the owner suggests some changes before merging, you can simply push these changes into your fork by repeating steps 3 and 4 and the pull request is updated automatically.

```
