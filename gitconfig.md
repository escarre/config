[user]
name = Elizabeth Carretto
email = elizabeth.carretto@bullhorn.com
[branch]
autosetuprebase = always
[color "diff"]
meta = yellow bold
whitespace = red reverse
[color "status"]
added = yellow
changed = green
untracked = cyan
[color "branch"]
current = yellow reverse
local = yellow
remote = green
[alias]
co = checkout
ci = commit
s = status
br = branch
lg = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset%s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
df = diff --color
dfm = diff master --color
dfrom = diff origin/master --color
[core]
editor = nano
autocrlf = input
eol = crlf
[push]
default = current
