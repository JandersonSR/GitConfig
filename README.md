# CUSTOM GitConfig commands

On terminal: 
  - git config --global core.editor code      //*change vscode to your gitconfig editor
  - git config --global --edit               //*open vscode gitconfig editor

//*create an alias just like the example*/

##[alias]
---
- s = !git status -s
- c = !git commit -m
- psh = !git push origin
- pll = !git pull origin
- check = !git checkout
- create = !git checkout -b
- l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s -%C(cyan)%cn, %C(green)%cr'

//*And know u have custom git commands, cheers ;)

![image](https://user-images.githubusercontent.com/45982396/193343140-9de9e40f-d3fc-4e28-a549-4fb5be3e589d.png)

![image](https://user-images.githubusercontent.com/45982396/193343921-50788b7a-c75b-4086-a446-322dd92da9a0.png)
