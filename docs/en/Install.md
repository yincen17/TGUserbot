# Installation
You can install TGUserbot automatically if you have Ubuntu, Termux or Windows.
If you aren't using Ubuntu you can install it manually. Now you can also install TGUserbot on a web hosting (000webhost, altervista ecc.).

Ubuntu
------
     curl https://raw.githubusercontent.com/peppelg/TGUserbot/master/installer/tguserbot_ubuntu_installer.sh | sudo bash
     cd TGUserbot
     
Termux
------
    curl https://raw.githubusercontent.com/peppelg/TGUserbot/master/installer/tguserbot_termux_installer.sh | bash
    cd TGUserbot

Windows
-------
Download the `.zip` file from https://t.me/TGUserbotReleases, extract it, start `cmd.bat` and type `php TGUserbot.phar`.

Web hosting
------------
1. Make a folder named `TGUserbot`
2. Inside `TGUserbot` folder, copy [index.php](https://raw.githubusercontent.com/peppelg/TGUserbot/master/web/index.php)
3. If you are using Altervista, enable S2S
4. Open `index.php` in `TGUserbot` from your browser

Manually
------------
First, install packages `git zip screen php php-mbstring php-xml php-gmp php-curl php-bcmath php-zip php-json php-cli`. Be sure to have PHP 7.1 or higher.

Then download TGUserbot with `mkdir TGUserbot && cd TGUserbot && wget https://github.com/peppelg/TGUserbot/raw/master/TGUserbot.phar && wget https://github.com/peppelg/TGUserbot/raw/master/bot.php`



### >>[Using TGUserbot](https://github.com/peppelg/TGUserbot/tree/master/docs/en/Use.md)<<
