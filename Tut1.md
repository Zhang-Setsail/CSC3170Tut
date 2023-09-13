```
cd ~
touch .bash_profile
open -e .bash_profile
```

add `
export PATH=${PATH}:/usr/local/mysql/bin
` in ./bash_profile file

or your self path

```
cd ~
touch .zshrc
open -e .zshrc
```

add `
source ~/.bash_profile
` in .zshrc file

`
source ~/.zshrc
` in terminal
