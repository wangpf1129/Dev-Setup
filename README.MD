# MacOS dev environment setup

Here is my memo for setting up the development environment on my Mac.

## Software

> Commonly used CLI and GUI

#### Formulae

```shell
brew install \
	docker \
	git \
	tokei \
	tldr \
	htop \
```

#### Casks

```shell
brew install --cask \
	1password \
	arc \
	chatgpt \
	fork \
	google-chrome \
	iterm2 \
	keka \
	orbstack \
	surge \
	mos \
	switchhosts \
	the-unarchiver \
	typora \
	utools \
	istat-menus \
	bob \
	visual-studio-code \
	xcodes \
	jetbrains-toolbox \
	input-source-pro \
```

## Terminal

#### plugins

```shell
plugins=(git history history-substring-search wd node npm web-search last-working-dir  zsh-autosuggestions  zsh-syntax-highlighting you-should-use)
```

- font-jetbrains-mono

- font-meslo-lg-nerd-font

- iterm2

- keka

- p11-kit

- powerlevel10k

- zoxide

#### alias

```shell
alias cls="clear"
alias p='pnpm'
alias cd="z"
alias ls="eza --icons=always --color=always --git"
```

## Nodejs

#### NVM- Node Version Manager

```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

#### PNPM- Fast, disk space efficient package manager

```shell
npm install -g pnpm
```
