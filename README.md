# PSR Log Slack

[![Build Status](https://travis-ci.org/dominionenterprises/psr-log-slack.svg?branch=master)](https://travis-ci.org/dominionenterprises/psr-log-slack)
[![Code Quality](https://scrutinizer-ci.com/g/dominionenterprises/psr-log-slack/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/dominionenterprises/psr-log-slack/?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/dominionenterprises/psr-log-slack/badge.svg?branch=master)](https://coveralls.io/github/dominionenterprises/psr-log-slack?branch=master)

[![Latest Stable Version](https://poser.pugx.org/dominionenterprises/psr-log-slack/v/stable)](https://packagist.org/packages/dominionenterprises/psr-log-slack)
[![Latest Unstable Version](https://poser.pugx.org/dominionenterprises/psr-log-slack/v/unstable)](https://packagist.org/packages/dominionenterprises/psr-log-slack)
[![License](https://poser.pugx.org/dominionenterprises/psr-log-slack/license)](https://packagist.org/packages/dominionenterprises/psr-log-slack)

[![Total Downloads](https://poser.pugx.org/dominionenterprises/psr-log-slack/downloads)](https://packagist.org/packages/dominionenterprises/psr-log-slack)
[![Monthly Downloads](https://poser.pugx.org/dominionenterprises/psr-log-slack/d/monthly)](https://packagist.org/packages/dominionenterprises/psr-log-slack)
[![Daily Downloads](https://poser.pugx.org/dominionenterprises/psr-log-slack/d/daily)](https://packagist.org/packages/dominionenterprises/psr-log-slack)

This is an implementation of [PSR-3](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md) reporting to [Slack](https://api.slack.com/) using [incoming webhooks](https://api.slack.com/incoming-webhooks).

## Requirements

PSR Log Slack requires PHP 7.0 (or later).

## Composer
To add the library as a local, per-project dependency use [Composer](http://getcomposer.org)! Simply add a dependency on `dominionenterprises/psr-log-slack` to your project's `composer.json`.
```sh
composer require dominionenterprises/psr-log-slack
```

## Contact
Developers may be contacted at:

 * [Pull Requests](https://github.com/dominionenterprises/psr-log-slack/pulls)
 * [Issues](https://github.com/dominionenterprises/psr-log-slack/issues)

## Run Unit Tests
With a checkout of the code get [Composer](http://getcomposer.org) in your PATH and run:

```sh
composer install
./vendor/bin/phpunit
