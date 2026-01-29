INstall
```bash
sh -c "$(curl -fsLS get.chezmoi.io)"
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply kiddiv
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git \${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel10k
git clone https://github.com/zsh-users/zsh-syntax-highlighting \${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/Aloxaf/fzf-tab \${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/fzf-tab

```
```bash
exec zsh

```

2.zsh-autosuggestions – автоматично пропонує команди з історії під час набору

zsh-syntax-highlighting – підсвічує синтаксис команд, показує помилки ще до виконання

fzf-tab – додає fuzzy-пошук при автодоповненні через Tab

zsh-interactive-cd – робить перехід між директоріями інтерактивним

colored-man-pages – додає кольори до man-сторінок для кращої читабельності

Також використано тему – powerlevel10k 

