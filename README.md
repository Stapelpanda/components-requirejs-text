# components-requirejs-text
RequireJS text for the @robloach/component-installer

Simple `composer.json` file to allow [requirejs-text](https://github.com/requirejs/text) to be installed by [RobLoach/component-installer](https://github.com/RobLoach/component-installer)

## Installing
Setup Composer to include this repository:

  	{
    	...
    	"require": {
      	...
      	"components/requirejs-text": "^2"
    	},
    	"repositories": [
    	  	{ "type": "vcs", "url": "https://github.com/StapelPanda/components-requirejs-text" }
    	]
  	}

Install using composer `composer update`

## Usage

Using `RequireJS`

    define(['jquery', 'text!woot.html'], function($, htmlTemplate){
	$('body').html(htmlTemplate);
    });