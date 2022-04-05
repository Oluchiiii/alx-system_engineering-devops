**alias ls="rm *"** Gives the alias command
**echo "hello $USER"** Prints hello user when user is the current user
**export PATH=$PATH:/action** adds /action to PATH
**echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))** counts the number of directories in PATH
**printenv** prints environmental variables
**BEST=School** creates a local variable
**export BEST=School** creates a global variable
