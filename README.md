# shell-profile
This is a shell configuration for Linux and OSX. This will make some changes:
- Change the PS1 variable on system environment
- Added some alias for shell
- Changed configuration for VI editor
- Changed configuration for GIT global

### Installation
- Clone this repository at home folder

- Enter your contact information at **.gitconfig**
```
[user]
   name = [Your name]
   email = [Your email]
```
- Edit the bash profile adding this code at end of file. Usually is **.bashrc** or **.bash_profile**
```shell
# LOAD CODEGIK PROFILE
if [ -f ~/.codegik_profile ]; then
  . ~/.codegik_profile
fi
```
