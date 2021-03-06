MyWin Keyboard Installer
=========================

##Introduction

- This package contains MyWin Keyboard Installation Script.

##Installation

- Type the following commands.

```
$ git clone https://github.com/naingyeminn/mywin-ubuntu.git
$ cd mywin-ubuntu
$ sudo make install
$ ibus-daemon -rdx
$ im-config -n ibus
$ gsettings set org.freedesktop.ibus.panel show 0
```

Now you can add the keyboard as follow.

- Click on **Text Entry Settings...**

![Text Entry Setting](https://raw.githubusercontent.com/naingyeminn/nym_blog_data/master/Photos/MyWin/ubuntu01.png)

- Click on **"+"** button and search **my-win** input. You will see **my-Win 2.3.3 Unicode 5.2**.

![input1](https://raw.githubusercontent.com/naingyeminn/nym_blog_data/master/Photos/MyWin/ubuntu02.png)

- Click on **Add**.

![input2](https://raw.githubusercontent.com/naingyeminn/nym_blog_data/master/Photos/MyWin/ubuntu03.png)

- Now you can change keyboard layout by pressing (**Super + Space**) key.

##Uninstallation

```
$ cd mywin-ubuntu
$ sudo make uninstall
```

##Contact

```
Naing Ye Minn
me@naingyeminn.com
website : http://naingyeminn.com
```
