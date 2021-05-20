# set_up_ssh
README only to set up ssh on linux


#first use:
ssh-keygen
# to create your key pair
#copy all of the public key text except for user@host
#paste this info to the setting on github in the ssh section
#go to your ssh directory and add in the following selection in the config file
Host github.com
 HostName github.com
 IdentityFile ~/.ssh/id_rsa_github
#make sure the key has 400 permissions and the config file has 600 permission
#then run the following git command
git remote set-url origin git@github.com:<Username>/<Project>.git
#you can copy this text from the clone scroll down
#now git push should work great
