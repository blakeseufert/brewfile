# Setup MacOS with Blake's Brewfile
MacOS Brewfile for apps and utility setup

# Usage

Open Terminal and paste:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Install Brew
```
brew bundle install
```

Get Brew File
```
curl -o brewfile https://raw.githubusercontent.com/blakeseufert/brewfile/main/brewfile.txt
brew bundle --file=curl brewfile.txt
```
