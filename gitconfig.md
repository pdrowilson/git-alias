[user]
	name = Pedro Wilson
	email = pdro.wilson@gmail.com
[core]
	editor = code --wait
[alias]
	c = !git add . && git commit -m 
	s = !git status -s
	l = !git log --pretty=format:'%C(yellow)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
	amend = !git add . && git commit --amend --no-edit
	pl = pull
	ps = push
	ck = checkout
	cl = clone
	b = branch
