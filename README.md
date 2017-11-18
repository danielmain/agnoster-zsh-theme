# btg.zsh-theme

This is a Fork of the original [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme)

This theme is optimized for people who want to see the current Bitcoin Gold USD Price and who use:

- Solarized
- Git
- Unicode-compatible fonts and terminals (I use iTerm2 + Menlo)


## What does it show?

- If the previous command failed (✘)
- User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile)
- Bitcoin Gold USD Price from www.coinmarketcap.com
- Git status
  - Branch () or detached head (➦)
  - Current branch / SHA1 in detached head state
  - Dirty working directory (±, color change)
- Working directory
- Elevated (root) privileges (⚡)

![Screenshot](https://user-images.githubusercontent.com/4303099/32984444-fb8fa72a-cca6-11e7-9755-f842bf6e9afc.png)

# Installation

## MacOs Users

- Install Homebrew
	```
	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
	```
- Install git and other tools using Homebrew 
	```
	brew install git curl wget
	```
- Install zsh using Homebrew
	```
	brew install zsh zsh-completions
	```
- Set zsh as your default shell
	```
	chsh -s $(which zsh)
	```
- Install oh-my-zsh
	```
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
	```
- Install Powerline fonts from https://github.com/powerline/fonts
- Set one of the Powerline fonts in your terminal emulator (iTerm or Terminal)
- Download the theme
	```
	wget https://raw.githubusercontent.com/danielmain/zsh-btg-theme/master/btg.zsh-theme -P ~/.oh-my-zsh/themes/
	```
- Edit your .zshrc and change the theme to
	```
	ZSH_THEME="btg"
	```

For Mac users, I highly recommend iTerm 2 + Solarized Dark

## Linux (debian based) Users

- Install git and other tools using Homebrew 
	```
	apt-get install git curl wget
	```
- Install zsh using Homebrew
	```
	apt-get install zsh
	```
- Set zsh as your default shell
	```
	chsh -s $(which zsh)
	```
- Install oh-my-zsh
	```
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
	```
- Install Powerline fonts from https://github.com/powerline/fonts
- Set one of the Powerline fonts in your terminal emulator (Eg. Gnome Terminal, Konsole, etc)
- Download the theme
	```
	wget https://raw.githubusercontent.com/danielmain/zsh-btg-theme/master/btg.zsh-theme -P ~/.oh-my-zsh/themes/
	```
- Edit your .zshrc and change the theme to
	```
	ZSH_THEME="btg"
	```

## Windows Users

- Format and install Liunx :-)


# Compatibility

**NOTE:** In all likelihood, you will need to install a [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts) for this theme to render correctly.
