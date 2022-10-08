# Tools I love ! 🤩
Sometimes you feel like a tool just makes sense. Over the years, I came up accross a few ones which I thought I might share !

# Web tools
1. [Protonmail](https://protonmail.com/) (+ Proton Calendar + Proton Drive + ProtonVPN)
2. [Notion](https://notion.so/)
3. [Figma](https://figma.com/)
4. [Bitwarden](https://bitwarden.com/)
5. [Spline](https://spline.design/)

# Software
1. [Tinkerwell](https://tinkerwell.app/)

# Firefox extensions
<details>
  <summary>Extensions</summary>
  
  1. Don't track me Google
  2. DuckDuckGo Privacy Essentials
  3. Facebook container
  4. Fake filler
  5. Fontanello
  6. Gesturify
  7. HTTPS everywhere
  8. Popup Blocker Ultimate
  9. Search by image
  10. Simple translate
  11. Temp mail
  12. Wappalyzer
  14. React Developer tools
  15. Vue.js devtools
  16. Webhint
</details>
  
# Ubuntu
## Gnome extensions
<details>
  <summary>Extensions</summary>
  
  1. Burn my windows
  2. Clipboard indicator
  3. Color picker
  4. Removable Drive Menu
  5. Screenshot Tool
  6. Lock keys
  7. Refresh Wifi Connections
  8. Remove Alt+Tab Delay v2
  9. NoAnnoyance v2
</details>

## CLI tools that will change your life

### [bat](https://github.com/sharkdp/bat)
>  _A cat(1) clone with syntax highlighting and Git integration. Once you've tried it, there is no coming back._

### [exa](https://github.com/ogham/exa)
> _A modern replacement for the venerable file-listing command-line program ls that ships with Unix and Linux operating systems, giving it more features and better defaults. It uses colours to distinguish file types and metadata. It knows about symlinks, extended attributes, and Git._

### [ripgrep](https://github.com/BurntSushi/ripgrep)
> _`ripgrep` is a line-oriented search tool that recursively searches the current directory for a regex pattern. By default, ripgrep will respect gitignore rules and automatically skip hidden files/directories and binary files._

### [fd](https://github.com/sharkdp/fd)
> _`fd` is a program to find entries in your filesystem. It is a simple, fast and user-friendly alternative to find._

### [fzf](https://github.com/junegunn/fzf)
> _`fzf` is a general-purpose command-line fuzzy finder._

### [duf](https://github.com/muesli/duf)
> _Disk Usage/Free Utility - a better `df` alternative._

### [litecli](https://github.com/dbcli/litecli)
> _A command-line client for SQLite databases that has auto-completion and syntax highlighting._

## Shell

### [Oh-my-zsh](https://ohmyz.sh/)
> _Once installed, your terminal shell will become the talk of the town or your money back! With each keystroke in your command prompt, you'll take advantage of the hundreds of powerful plugins and beautiful themes. Strangers will come up to you in cafés and ask you, "that is amazing! are you some sort of genius?"_

Theme : `robbyrussell` (or [pure](https://github.com/sindresorhus/pure))  

<details>
  <summary>Plugins</summary>
  
  1. zsh-autosuggestions
  2. zsh-syntax-highlighting
  3. git
  4. npm
  5. colored-man-pages
  6. extract
  7. gitfast
  8. laravel
  9. node
  10. gitignore
  11. heroku
  12. autoupdate
  13. sudo
</details>

<details>
  <summary>Options</summary>
  
  1. `setopt autocd`
  2. `unsetopt nomatch`
</details>

<details>
  <summary>Aliases</summary>
  
  ```bash
  ## long commands
  alias apt-deb="sudo apt install ./*.deb -y && rm *.deb"

  ## alternative commands & extra args
  alias du="duf"
  alias cat="bat --theme=OneHalfDark"
  alias find="fdfind"
  alias grep="rg"
  alias diff="colordiff"
  alias ls="exa -lg"
  alias ll="exa -lg"
  alias la="exa -alg"
  alias sqlite="litecli"
  alias sqlite3="litecli"
  alias fzf="fzf --color=dark"

  ## shorthands
  alias c="code"
  alias s="sudo"
  alias arti='php artisan'

  ## configs
  alias zshconfig="nano ~/.zshrc"
  alias zshup="source ~/.zshrc"
  ```
</details>

<details>
  <summary>Functions</summary>
  
  ```bash
  function lazygit() {
    git add -A
    git commit
    git push
  }
  function update() {
    sudo apt update
    sudo apt dist-upgrade -y
    sudo apt autoremove -y
    sudo apt clean
    sudo snap refresh
    notify-send "Update" "System has been successfully updated." -t 500
  }
  ```
</details>

## Search bar
### [Ulauncher](https://ulauncher.io/)
> _Ulauncher is a fast application launcher for Linux. It's is written in Python, using GTK+, and features: App Search (fuzzy matching), Calculator, Extensions, Shortcuts, File browser mode and Custom Color Themes_

Theme : [WhiteSur Dark](https://github.com/Raayib/WhiteSur-Dark-ulauncher)
