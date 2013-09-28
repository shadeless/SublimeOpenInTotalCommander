Open In Total Commander
===========================
Author: Björn Carlsson

License: MIT

https://github.com/HackerBaloo/SublimeOpenInTotalCommander

About
-----
A sublime plugin that allows you to open selected file
(by pressing'ctrl+shift+o') in Total Commander.

Usage
-----
All you need to do is to press 'ctrl+shift+o' and
Open in Total Commander will open the selected file in Total Commander.

Configuration
-------------
Default:

    // set executable path
    "exe": "C:/Dropbox/Apps/Total Commander/Totalcmd64.exe",
    // {path} refers to open file/buffer
    "aruments": "/O /P=L /L=\"{path}\""

Installation
------------
**With Package Control:** The easiest way to install Open In Total Commander is
by using the [Package Control plugin]
(http://wbond.net/sublime_packages/package_control).

**Without Git:** Download the latest source from
[GitHub](https://github.com/HackerBaloo/SublimeOpenInTotalCommander) and copy
the Open In Total Commander folder to your Sublime Text 2 "Packages" directory.

**With Git:** Clone the repository in your Sublime Text 2 "Packages" directory:

    git clone https://github.com/shadeless/SublimeOpenInTotalCommander

The "Packages" directory can be found in the following locations:

* OS X:

        ~/Library/Application Support/Sublime Text 2/Packages/

* Linux:

        ~/.config/sublime-text-2/Packages/

* Windows:

        %APPDATA%/Sublime Text 2/Packages/

