# Neo Vim Install and config
Установка для Linux не трубуется, просто скачиваем **nvim.appimage** и запускаем его:
```bash
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
./nvim.appimage
```
Прописываем алиас в **.bashrc** или **zshrc**:
```bash
alias nvim="~/./nvim.appimage"
```
Создаем директорию и конфигурационный файл:
```bash
mkdir -p ~/.config/nvim/
touch ~/.config/nvim/init.vim
```
