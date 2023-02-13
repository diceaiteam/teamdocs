# Writing and publishing on our github pages doc
A brief guide to building the documentation tool from github, writing and publishing on the github pages

## Synchronize source code from remote repo

### Cloning to local
1. Cloning the source code repo from [our github repo](https://github.com/diceaiteam/teamdocs) using git;
2. In the local cloned project, edit the pages;
3. Preview content in local server using `mkdocs serve`

### Commit Locally
1. `git add ` to add the changes to git
2. `git commit` to commit to the local git 

### Commit remotely
1. Make sure local git has access to remote repo (an easy way would be to add collaborator);
2. Use `git push origin main` to push to origin's main branch.

## build the site and publish
1. Use `mkdocs build` to build the documentation. The output dir can be specified with -d option;
2. Make sure the built dir is in gh-pages branch which is the default branch of publishing page;
3. Connect the build site with [remote repo](https://github.com/diceaiteam/diceaiteam.github.io) if not already done;
4. Push with overwrite: `git push -f origin gh-pages`;
5. Check [Actions](https://github.com/diceaiteam/diceaiteam.github.io/actions) of the github project and make sure the deployment is successful.