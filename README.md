# Useful configuration

## You need to have tmux and tpm installed

debian/ubuntu
```
sudo apt install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## Font with the needed icons: https://www.nerdfonts.com/font-downloads 

```
mkdir ~/.local/share/fonts
unzip YOUR_FONT.zip -d ~/.local/share/fonts/
fc-cache ~/.local/share/fonts
```

Once done, you might want to change the font for your OS and terminal

## clone


```
git clone git@github.com:sobitoks/tmux.git ~/.config/tmux/
```

## Reload config

Inside tmux
```
tmux source ~/.config/tmux/tmux.conf
<prefix> + I
```
