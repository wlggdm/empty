# empty
用来下载chromium相关工程的代码


下载相应版本的chromium的源码包并解压:
```shell
mkdir -p ~/chromium/src
tar *.tar.gz -C ~/chromium/src
cd ~/chromium
gclient config --name=src https://github.com/wlggdm/empty.git
gclient sync
