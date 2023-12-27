# php.path.variable.macos

`php -v` version control then returns zsh: command not found: php

## Homebrew Path Variable Define Command
`export PATH="/usr/local/opt/php/bin:$PATH"`

## Add Variable Path to .zshrc file
`echo 'export PATH="/usr/local/opt/php/bin:$PATH"' >> ~/.zshrc`

## Save Changes
`source ~/.zshrc`
