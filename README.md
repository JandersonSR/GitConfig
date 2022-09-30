# CUSTOM GitConfig commands

First open your terminal and do the following:

change vscode to your gitconfig editor
---
 ```git config --global core.editor code ``` 
   
open vscode gitconfig editor
 ---
```git config --global --edit ```               


create an alias just like the example bellow

```
[user]
	email = jandersonrodriguesir@gmail.com
	name = JandersonSR
[core]
	editor = code
[alias]
	s = !git status -s
	c = !git commit -m
	psh = !git push origin
	pll = !git pull origin
	check = !git checkout
	create = !git checkout -b
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s -%C(cyan)%cn, %C(green)%cr'
```

//*And know u have custom git commands, cheers ;)
![image](https://user-images.githubusercontent.com/45982396/193343921-50788b7a-c75b-4086-a446-322dd92da9a0.png)
