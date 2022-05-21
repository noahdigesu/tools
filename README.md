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

## [bat](https://github.com/sharkdp/bat).
>  _A cat(1) clone with syntax highlighting and Git integration. Once you've tried it, there is no coming back._

## [Ulauncher](https://ulauncher.io/)
> _Ulauncher is a fast application launcher for Linux. It's is written in Python, using GTK+, and features: App Search (fuzzy matching), Calculator, Extensions, Shortcuts, File browser mode and Custom Color Themes_

## [Oh-my-zsh](https://ohmyz.sh/)
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
</details>

<details>
  <summary>Options</summary>
  
  1. `setopt autocd`
  2. `unsetopt nomatch`
</details>

<details>
  <summary>Aliases</summary>
  
  ```bash
  alias hyperconfig="nano ~/.hyper.js"
  alias zshconfig="nano ~/.zshrc"
  alias zshup="source ~/.zshrc"
  alias cat="bat"
  alias python='ipython3'
  alias arti='php artisan'
  alias c="code"
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
    notify-send "Update" "System has been successfully updated." -t 500
  }
  ```
</details>

## [Hyper.js](https://hyper.is/)
> _Possibly the most beautiful and customizable terminal you can get._

Theme : [hyper-snazzy](https://www.npmjs.com/package/hyper-snazzy)  
<details>
  <summary>Plugins</summary>
  
  1. [hyperpower](https://www.npmjs.com/package/hyperpower)
  2. [hyper-drop-file](https://www.npmjs.com/package/hyper-drop-file)
  3. [hyper-statusline](https://www.npmjs.com/package/hyper-statusline)
</details>
