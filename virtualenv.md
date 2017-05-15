# How to install Virtual env?

You can install Virtualenv along with virtualwrappers

To install virtual env in Ubuntu

```
sudo pip install virtualenv
```

```
Sudo pip install virtualenvwrapper
```

After install virtualenv and virtualwappers

copy this to your bashrc file.
and restart terminal.

To open bashrc

```
vim ~/.bashrc
```
# Create directory for project 

```
mkdir ~/.virtualenvs
```
and copy this to last line of the file

```
export PROJECT_HOME=~/.virtualenvs
```

```
. /usr/local/bin/virtualenvwrapper.sh
```

# To Create a virtualenv
```
mkproject PROJECTNAME
```

# To workon a virtualenv
```
workon PROJECTNAME
```

This will activate the virtualenv
