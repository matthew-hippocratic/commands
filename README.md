# commands
this is a repo to hold all my commands
one example use case is a list of aliases that I can import to new machines

### Applying the bash_rc_content to your bashrc

#### First verify it is correct
```
curl -s https://raw.githubusercontent.com/matthew-hippocratic/commands/refs/heads/main/bash_rc_content
```

#### Then apply
bashrc
```
curl -s https://raw.githubusercontent.com/matthew-hippocratic/commands/refs/heads/main/bash_rc_content >> ~/.bashrc && source ~/.bashrc
```

zshrc
```
curl -s https://raw.githubusercontent.com/matthew-hippocratic/commands/refs/heads/main/bash_rc_content >> ~/.zshrc && source ~/.zshrc
```