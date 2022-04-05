**alias ls="rm *"** Gives the alias command
**echo "hello $USER"** Prints hello user when user is the current user
**export PATH=$PATH:/action** adds /action to PATH
**echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))** counts the number of directories in PATH
**printenv** prints environmental variables
**BEST=School** creates a local variable
**export BEST=School** creates a global variable
**echo $(($TRUEKNOWLEDGE + 128))** is an arithmethic expression(addition) of what's in the bracket
**echo $(($POWER / $DIVIDE))** gives the arithmethic expression(division) of the bracket contnet
**echo $(($BREATH**$LOVE))** gives arithmethic expression(rates to power) of the bracket
**echo $((2#$BINARY))** gives arithmethic expression(conversion to binary) of bracket
