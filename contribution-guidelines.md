# Sharing your Kirby project on Github 
If you're not familiar with github, a great place to start is to create an account and follow the [guide to create your first repository.](https://help.github.com/articles/create-a-repo/). 

## IMPORTANT - Remove license and other sensitive content
Not everything must be shared. Your license key for instance in your configuration file should absolutely not be shared. A great way to tell github not to upload certain fils is to use a .gitignore file. It gives github directives on which folders or files to ignore during a commit. Here is a standard gitignore file to remove all content, account and configuration files:
```
/assets/avatars
/content
/site/accounts
/site/cache
/site/config
/thumbs
```

Read more about securing your Kirby repo on Fabian's [forum post](https://forum.getkirby.com/t/github-repo-security-advice/4157?u=thiousi). 

## Contributing to the kirby-repos list 
1. Verify that the repository hasn't been listed or submitted (see pull requests) already 
2. Verify that no sensitive information is available in the repository 
3. Edit the Readme.md file
4. Add the repository at the end of the list using the following format: `[username/repo name](repo url) | description`
5. Say why you're proposing the addition at the bottom of the page and than click on "propose file change" 
6. Submit the [pull request](https://help.github.com/articles/using-pull-requests/)! 
