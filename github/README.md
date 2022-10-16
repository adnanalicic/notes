# How to rewrite git history?

1. Do a backup of your repository before executing next step.
2. clone your repository with --mirror flag
3. go inside your repo and execute
	java -jar ../bfg.jar --delete-files *-secrets-*
to delete all files of that contain pattern -secrets-
