### MacOs下Vscode的vim模式无法持续按键
在终端里面输入以下命令关闭Mac的该功能：
```
# Disable Mac's "Press&Hold" feature
$ defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false
```
如果要恢复的话：
```
# Re-enable this feature
$ defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool true
```
然后重启Vscode就可以了


### zip在不解压的情况下直接压入对应目录的文件
TODO:

