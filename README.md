# homebrew

yum -> rhel/CentOS
apt -> ubuntu
apk -> alpine
**homebrew -> macOS**

* `homebrew` is a package manager for macOS
* homebrew packages are called `formulae`
* homebrew manages a list of formulae in a place called `homebrew/core` 
* `Core` means people at homebrew maintain the formulae list
* `tap` lets you add third party formulae to homebrew which can be used for
* installation
* `homebrew/cask` lets you install GUI applications like Chrome, Atom etc



### Homebrew Basics 

How to install homebrew?

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

How to update homebrew?
```
brew update
```

How to install a package?
```
brew install <package_name>
```

How to upgrade a specific package?
```
brew upgrade <package_name>
```

How to upgrade all packages
```
brew upgrade # but I recommend do not do this. 
```

How to downgrade a package?
```
brew search <package_name>
brew install <package_name>@1.0
brew unlink <package_name>
brew link <package_name>@1.0 --force
```

How to delete a package?
```
brew uninstall <package_name>
```

### Brew tap



