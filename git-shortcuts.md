A different way to format your logs:

## Instructions

1. Go to your home folder
2. Create a file named ``.aliases``
3. Paste the folowing line:

> alias gl="git log --graph --pretty=format:'%Cred%h%Creset %an: %s - %Creset %C(yellow)%d%Creset %Cgreen(%cr)%Creset' --abbrev-commit --date=relative --all"

4. Open bash-profile
5. Place the following line:

> source .aliases

6. Restart terminal
