# .gitconfig
```ini
[user]
	name = XXXXXXXXXX
	email = YYYYYYYYY
	signingkey = ZZZZZZZZZZZ
[commit]
	gpgsign = true
[alias]
	last 	= "log -1 HEAD"
	unstage = "reset HEAD --"
	s	= "status"
	f	= "fetch"
	pl	= "pull"
	ps	= "push"
[pull]
	rebase = true
[filter "lfs"]
	clean 	 = git-lfs clean -- %f
	smudge 	 = git-lfs smudge -- %f
	process  = git-lfs filter-process
	required = true
[gpg]
	program  = C:\\Program Files (x86)\\GnuPG\\bin\\gpg.exe
[credential "helperselector"]
	selected = store
```
