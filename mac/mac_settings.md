# Mac Settings

## Install brew
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

> echo 'eval $(/opt/homebrew/bin/brew shellenv)' >> /Users/$USER/.zprofile

> eval $(/opt/homebrew/bin/brew shellenv)

---
## Install oh-my-zsh
> \$ sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)   

### Change Prompt for oh-my-zsh
>\# edit default theme  
\$ vim ~/.oh-my-zsh/themes/robbyrussell.zsh-theme  
  
change second line from 
> PROMPT+=' %{$fg[cyan]%}%c%{$reset_color%} $(git_prompt_info)'

to 
> PROMPT+=' %{$fg[cyan]%}%~%{$reset_color%} $(git_prompt_info)'

---

## Enable Mouse Shortcut keys
install [Mac Mouse Fix](https://mousefix.org/)
> ex : enable previous key for logi M590 mouse

---
## Install Liu IME
> curl https://raw.githubusercontent.com/rwu823/liu/master/install.sh | sh
### Add IME
![Liu1](https://raw.githubusercontent.com/rwu823/liu/master/screens/1.png)
![Liu2](https://raw.githubusercontent.com/rwu823/liu/master/screens/2.png)

---
