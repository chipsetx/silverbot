SilverBot
=========

Overview
--------
SilverBot is a simple IRC bot framework written in PHP. It is crazy-easy to use and supports plugins with a fair amount of flexibility. Included in the repo are two basic pre-built plugins, one for user authentication and access control, and one for channel joining/parting.

Requirements
------------
* PHP 5.2.0 or higher
* Pear Console_CommandLine module

Usage
-----
1. Download the code
2. Edit as needed (it's pretty well commented)
3. Copy config.ini-example to config.ini and make changes as needed
4. Run the bot.

    php bot.php

5. (Optional) Use command line options to run the bot differently

    php bot.php --help

Plugins
-------
SilverBot supports all kinds of plugins, and there is a separate plugins repository called '[silverbot-plugins](https://github.com/thesilvervestgroup/silverbot-plugins)'
Plugins live in the 'plugins' directory with your bot, and are automatically loaded upon startup.

License
-------
This is dual-licensed under MIT and LGPL or something, so go nuts.
