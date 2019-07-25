# ElectronParticleClock

This is a minimal clock. The first demo I made for learning electron.

### Dependencies

NodeJs
npm tools
Electron

### Quick Start

    npm install
    npm start

### Pack for MacOS

    # install package tools
    sudo npm install -g asar
    sudo npm install -g electron-packager
    # pack your program
    npm run pack

### Pack for Windows

    # install package tools
    npm install -g electron-packager
    # pack your program
    npm run dist-win

### Pack as one file for Windows

When you pack your electron application on windows, you will find there are many files rather than one exe file.

If you want to pack them as an installation exe:

Download [Inno Setup](https://pc.qq.com/detail/13/detail_1313.html) and open startup.iss

Edit the path in startup.iss

Click Build.

And you will get an installation file. Send it to others so they can install your program.

Ref:
[electron安装+运行+打包成桌面应用+打包成安装文件+开机自启动](https://www.cnblogs.com/kakayang/p/9559777.html)

The part of particle clock is found in an open-source website,
I think you can find this project on codepen.io.

And I want to develop it further as Electron application.

### Demo

![](https://i.loli.net/2019/07/26/5d39f3409c03713588.jpg)
