# bash-config
Personal configuration for the bash shell.

## Setup

1. Copy the `.bash` folder to your home directory.

2. Update `~/.bash_profile` to:

```
# Initialize from .bashrc if found.
if [ -f ~/.bashrc ];
then
  source ~/.bashrc
fi

source ~/.bash/bash_profile
```

3. Update `~/.bashrc` to:

```
# Load from source controlled location.
source ~/.bash/bashrc
```