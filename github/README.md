# How to rewrite git history?

Probably on every project at some point sensitive data is pushed to git. 
Here is an easy way to remove all that data from the whole history.

1. Do a backup of your repository before executing next step.
2. Clone your repository with --mirror flag
3. Go inside your repo and execute

	`java -jar ../bfg.jar --delete-files *-secrets-*`

    to delete all files of that contain pattern -secrets- . The jar file is part of the this repository.


For more details take a look at: https://rtyley.github.io/bfg-repo-cleaner/