## macbook-setup

This is a simple macbook setup guide for non-exp macbook user

**Please open terminal and run the following commands from top to bottom**

### Common

Homebrew - package manager
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" # brew
```

Homebrew cask - applications pool (^(OO)^)
```
brew tap caskroom/cask
```

Base applications
```
brew cask install macdown
brew cask install google-chrome
brew cask install slack
brew cask install adobe-creative-cloud
brew cask install iterm2
brew cask install sourcetree
```

Text editors
```
brew cask install sublime-text

or

brew cask install atom
```

Development enviroment
```
brew install rbenv
brew install node@6
brew install homebrew/apache/httpd24
brew install nginx
brew install mysql
brew install postgresql
brew install redis
```

Setup npm path
```
echo 'export PATH="/usr/local/opt/node@6/bin:$PATH"' > ~/.bash_profile
source ~/.bash_profile
```

Grunt
```
npm install -g grunt-cli
```

Vue
```
npm install -g vue-cli
```

SASS
```
gem install sass scss_lint

if you have problem with permission denied error

sudo gem install sass scss_lint
```

Ruby
```
rbenv install 2.3.4
rbenv rehash
rbenv global 2.3.4
```

Rails and bundler
```
gem install rails --version 5.0.3
gem install bundler
```
