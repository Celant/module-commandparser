# ChannelManager Module
[![Build Status](https://scrutinizer-ci.com/g/WildPHP/module-commandparser/badges/build.png?b=master)](https://scrutinizer-ci.com/g/WildPHP/module-commandparser/build-status/master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/WildPHP/module-commandparser/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/WildPHP/module-commandparser/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/wildphp/module-commandparser/v/stable)](https://packagist.org/packages/wildphp/module-commandparser)
[![Latest Unstable Version](https://poser.pugx.org/wildphp/module-commandparser/v/unstable)](https://packagist.org/packages/wildphp/module-commandparser)
[![Total Downloads](https://poser.pugx.org/wildphp/module-commandparser/downloads)](https://packagist.org/packages/wildphp/module-commandparser)

This module allows the bot to parse commands given by users in channels.

## System Requirements
If your setup can run the main bot, it can run this module as well.

## Installation
To install this module, we will use `composer`:

	composer require wildphp/module-commandparser

That will install all required files for the module. In order to activate the module, add the following line to your `config.neon`, section `modules`:

	- WildPHP/Modules/CommandParser/CommandParser

Make sure to include a tab character in front. The bot will run the module the next time it is started.

## License
This module is licensed under the GNU General Public License, version 3. Please see `LICENSE` to read it.