# dSSH
dSSH (Docker SSH) is a function made for ZSH. It simply autofills the command `dssh` (alias of `docker exec -it xx /bin/bash`) with the names of active containers. Just simply tab through the active containers!

![Example](https://raw.githubusercontent.com/innovato/dssh/master/example.gif)

## How do I install this plugin?
First you need [Oh-My-ZSH](https://ohmyz.sh/), then simply run `curl https://raw.githubusercontent.com/innovato/dssh/master/dssh.txt >> ~/.zshrc` and start a new instance of your terminal.

Just enter `dssh <tab> <tab>` and there you go!

**Heads up!**
This plugin only works if your container works with `bash`. If your container works with `sh`, then simply adjust the script (just change `/bin/bash` to `/bin/sh` in [dssh.txt:5](https://github.com/innovato/dssh/blob/master/dssh.txt#L5)). In the future we might create a smarter plugin.
