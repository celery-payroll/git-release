# git-release

### Install git python
``` bash
pip3 install gitpython
```

### Download from source
``` bash
cd /Users/<user>/repos
git clone https://github.com/wiebekn/git-release.git
cd git-release
```

### Make symlink so you can run it from everywhere
``` bash
ln -s git-release /usr/local/bin/git-release
```

### Copy template configfile to your project
``` bash
cp .gitrelease /Users/<user>/repos/myProject
```
### Usage
change .gitrelease to your needs
and run 
``` bash
git-release
```
