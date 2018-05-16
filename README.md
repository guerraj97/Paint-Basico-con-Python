# Paint-Basico-con-Python
Codigo basico para un paint simple, con una brocha utilizando Python 3 y Pygame
En caso de utilizar MacOS es importante considerar instalar lo siguiente:

Create and add the following to ~/.bash_profile:
     # Homebrew binaries now take precedence over Apple defaults
     export PATH=/usr/local/bin:$PATH

Install Apple Xcode command line tools:
xcode-select --install

Install XQuartz: http://xquartz.macosforge.org/landing/

Install homebrew:
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

Install Python3 "proper" and packages we’ll need for installing PyGame from bitbucket:
brew install python3 hg sdl sdl_image sdl_mixer sdl_ttf portmidi

Install PyGame:
pip3 install hg+http://bitbucket.org/pygame/pygame

Restart the Mac for XQuartz changes

Esta version esta verificada y probada al 15 de mayo de 2018. 
