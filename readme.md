# Story Engine WebHook plugin for WordPress
This plugin creates an endpoint for Story Engine to publish it's content.

## Requirements
* WordPress version 4.9 and up
* PHP 5.6 and up

## Plugin install
...

## Packagist
The plugin is pushed to Packagist for usage via composer if wanted.

## Official WordPress repository
The plugin is published to the official WordPress repository at [https://wordpress.org/plugins/](https://wordpress.org/plugins/).

## Development

### Git Workflow
Releases of this plugin is version controlled via Git Flow with develop and master branches.

### Development environment
Please contact us to get more info about development environment provided to this plugin.

### Tests locally with phpunit
Attention! `composer update` before any unit testing!
In the plugin root folder:
`vendor/bin/phpunit`

### Code Style Sniff locally
PSR is used, validate style with:
Attention! `composer update` before any style check!
`vendor/bin/phpcs --ignore=*/vendor/* .`

## Data
Gist example data (incoming json to endpoint): [https://gist.github.com/chredd/05dcdde86a48c8558ba70c5fe95514c5](https://gist.github.com/chredd/05dcdde86a48c8558ba70c5fe95514c5)
