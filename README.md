## My Tmux Configs

### Usage

#### 0. requirement
- tmux
- [reattach-to-user-namespace](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard)
```sh
brew install tmux
brew install reattach-to-user-namespace
```
#### 1. add tmux.confg
```
curl https://raw.githubusercontent.com/padma0/tmux/master/.tmux.conf > ~/.tmux.conf
```
#### 2. add tpm
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
#### 3. install plugins
```
tmux
# then press prefix + I
<Ctrl-q> <Shift-i>
```
#### 4. Powerline configs
```
git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
```
In iterms2:
Preference -> Profiles -> Text -> Non-ASCII Font -> Change Font -> Inconsolata for Powerline
#### 5. That's it! Enjoy!
