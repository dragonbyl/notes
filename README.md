1. google-chrome不能以root用户运行的解决方法
  打开/usr/share/applications/google-chrome.desktop文件, Exec那句加上--user-data-dir, 或者右键属性/应用程序 加上--user-data-dir.
2. 非常好用的linux发行版
  porteus 2.1 3.0 非常小巧, 可以直接放u盘, 从u盘启动, 类似的还有slax, 都是基于slackware.
  sms 是一个功能齐全的服务器版本, 省去了你搭建服务器的烦恼，小巧易用.
3. cat /etc/slackware-version
4. echo -e "\nPATH=\$PATH:/opt/armgcc/bin/" >> ~/.bashrc 
  source ~/.bashrc
5. whereis kicad