# dSSH
dSSH (Docker SSH) is a function made for ZSH. It simply autofills the command `dssh` (alias of `docker exec -it xx /bin/bash`) with the names of active containers. Just simply tab through the active containers!

## How do I install this plugin?
First you need [Oh-My-ZSH](https://ohmyz.sh/), then simply run `curl https://raw.githubusercontent.com/innovato/dssh/master/dssh.txt >> ~/.zshrc` and start a new instance of your terminal.

Just enter `dssh <tab> <tab>` and there you go!
