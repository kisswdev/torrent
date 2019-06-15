# torrent
🚀 A Nex-Gen Private Torrent Tracker (Aimed For Movie / TV Use) https://unit3d.org


UNIT3D Logo

💛A Big Thanks To All Our Contributors and Patrons💛

   StyleCI  Discord chat   

Table of Contents
Introduction
Some Features
Requirements
Installation 4.1 Automated-Installer 4.2 Manual Install
Updating
Packages
Version Support Information
Security
Contributing
License
Homestead (For local developement)
Demo
Donate
Contributors
Special Thanks
📄 Introduction
I have been developing a Nex-Gen Torrent Tracker Software called "UNIT3D." This is a PHP software based off the lovely Laravel Framework -- currently Laravel Framework 5.8.16, MySQL Strict Mode Compliant and PHP 7.1 Ready. The code is well-designed and follows the PSR-2 coding style. It uses a MVC Architecture to ensure clarity between logic and presentation. As a hashing algorithm of Bcrypt or Argon2 is used, to ensure a safe and proper way to store the passwords for the users. A lightweight Blade Templating Engine. Caching System Supporting: "apc,” "array,” "database,” "file," "memcached," and "redis" methods. Eloquent and much more!

💎 Some Features
UNIT3D currently offers the following features:

Internal Forums System
Staff Dashboard
Faceted Ajax Torrent Search System
BON Store
Torrent Request Section with BON Bounties
Freeleech System
Double Upload System
Featured Torrents System
Polls System
Extra-Stats
PM System
Multilingual Support
TwoStep Auth System
DB + Files Backup Manager
RSS System
and MUCH MORE!
✅ Requirements
A Web server (NGINX is recommended)
PHP 7.1.3 + is required (7.2 for Argon2 Support)
Dependencies for PHP,
php-curl -> This is specifically needed for the various APIs we have running.
php-intl -> This is required for the Spatie\SslCertificate.
php-zip -> This is required for the Backup Manager.
Crontab access
A Redis server
MySQL 5.7 + or MariaDB 10.2 +
TheMovieDB API Key: https://www.themoviedb.org/documentation/api
OMDB API Key: http://www.omdbapi.com/
A decent dedicated server. Dont try running this on some crappy server!
Processor: Intel  Xeon E3-1245v2 -
Cores/Threads: 4c/8t
Frequency: 3.4GHz /3.8GHz
RAM: 32GB DDR3 1333 MHz
Disks: SoftRaid  2x240 GB   SSD
Bandwidth: 250 Mbps
Traffic: Unlimited
Is Under $50 A Month
💻 Installation
NOTE: If you are running UNIT3D on a non HTTPS instance you MUST change the following configs.

config/session.php  <-- HTTPS Only Cookies must be set to false
config/secure-headers.php   <-- HTTP Strict Transport Security must be set to false
config/secure-headers.php   <-- Content Security Policy must be disabled
Automated Installer
A UNIT3D Installer has been released by Poppabear.

git clone https://github.com/poppabear8883/UNIT3D-INSTALLER.git installer
cd installer
sudo ./install.sh
Check it out here for more information: https://github.com/poppabear8883/UNIT3D-INSTALLER

Video Tutorial Can Be Seen Here: https://www.youtube.com/watch?v=f2tiMWZ3KbA

Manual Install
If you rather setup UNIT3D manually you can follow the instructions here: http://docs.unit3d.org/manual_install.html

📖 Documentation
Repo - https://github.com/HDInnovations/UNIT3D-Docs Site - http://docs.unit3d.org

💻 Updating
php artisan git:update

Video Tutorial Can Be Seen Here: https://www.youtube.com/watch?v=tlNUjS1dYMs

📦 Packages
Here are some packages that are built for UNIT3D.

An artisan package to import a XBTIT database into UNIT3D.
An artisan package to import a Gazelle database into UNIT3D.
An artisan package to import a U-232 database into UNIT3D.
🚨 Version Support Information
Version	Status	PHP Version Required
1.9.3	Active Support 🚀	>= 7.3
1.9.2	Active Support 🚀	>= 7.2
1.0 to 1.9.1	End Of Life 💀	>= 7.1.3
🔒 Security
If you discover any security related issues, please email unit3d@protonmail.com instead of using the issue tracker.

💪 Contributing
Please see CONTRIBUTING and CODE_OF_CONDUCT for details.

📝 License
UNIT3D is open-sourced software licensed under the GNU General Public License v3.0.

As per license do not remove the license from sourcecode or from footer in /resources/views/partials/footer.blade.php

💻 Demo
URL: https://unit3d.org

Username: UNIT3D

Password: UNIT3D

Demo is reset every 48 hours!

⭐️ Support UNIT3D
You can support my work if you are enjoying UNIT3D, this really keeps me up for fixing problems and adding new features. Also helps pay for the demo server + domain. Plus some beer to keep me sane. Some folks have asked me if it's possible to do a one-time donation, or if I accept cryptocurrency. Yes, and yes!

Patreon:

Bitcoin (BTC) - 3HUVkv3Q8b5nbxa9DtXG1dm4RdTJaTFRfc

Bitcoin Cash (BCH) - qp3wgpnwzpj4v9sq90wflsca8p5s75glrvga9tweu2

Ether (ETH) - 0x5eFF42F65234aD9c6A0CA5B9495f3c6D205bBC27

Litecoin (LTC) - MDLKyHzupt1mchuo8mrjW9mihkKp1LD4nG

💙 Contributors
Thanks goes to these wonderful people (emoji key):

HDVinnie
HDVinnie
💻 🎨 📖	Everett (Mike) Wiley
Everett (Mike) Wiley
💻	singularity43
singularity43
💻	VerioPL
VerioPL
🌍	Artyum
Artyuum
🎨	Morgan Wong
Morgan Wong
🌍
❤️ Special Thanks
 
