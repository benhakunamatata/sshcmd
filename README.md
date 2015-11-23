# sshcmd
ssh command line


# Problem and Error Message
ARNING: REMOTE HOST IDENTIFICATION HAS CHANGED!     @
IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!
# Solution
ssh-keygen -R myserver.com
ssh -K myserver.com

