# RawPHP Framework

[![Build Status](https://travis-ci.org/slimphp/Slim.svg?branch=3.x)](https://travis-ci.org/slimphp/Slim)
[![Coverage Status](https://coveralls.io/repos/github/slimphp/Slim/badge.svg?branch=3.x)](https://coveralls.io/github/slimphp/Slim?branch=3.x)
[![Total Downloads](https://poser.pugx.org/slim/slim/downloads)](https://packagist.org/packages/partner/rawphp)
[![License](https://poser.pugx.org/slim/slim/license)](https://packagist.org/packages/partner/rawphp)

RawPHP is powerful and robust PHP framework that helps people from different PHP backgrounds work on the same project seamlessly. You can write Laravel, CakePHP, Slim, Symphone and Procedural PHP code inside it and it all works perfectly. Its the PHP Framework for everyone. RawPHP was built for teams with ever changing team members.

RawPHP comes with complete user authentication system built-in and ready to use out of the box. 

## Installation
There are two ways to install RawPHP:

* The first way, (recommended) is to use [Composer](https://getcomposer.org/) to install RawPHP.
Navigate to the folder in your computer where you wish to install RawPHP, then run the below code in your command line
```
$ composer create-project --prefer-dist partner/rawphp
```

* The second way (only use this if the first method doesn't work for you) is to clone `https://github.com/rawphp-framework/rawphp.git` into your local machine, then CD into it and run `composer install` in your command line. If you don't have composer already installed in your system, do download and installed  [Composer](https://getcomposer.org/) . 


Both methods install RawPHP and all required dependencies. RawPHP requires PHP 5.5.0 or newer.

## Usage

There are two ways to run RawPHP

### PHP's inbuilt server
After RawPHP has installed, you can run it by using the built-in PHP server. Navigate to the root folder and run the below command:
```
$ php -S localhost:8000 -t public

```
Going to http://localhost:8000/ will now display your default Homepage.

### Wamp, LAMP or XAMP server
Otherwise, you can just put it in your wamp/www or xxamp htdocs folder and access it by visiting the url on your browser `localhost/your-rawphp-folder/public


For more information on how to configure your web server, see the [Documentation](https://www.slimframework.com/docs/start/web-servers.html).

## Tests

To execute the test suite, you'll need phpunit.

```bash
$ phpunit
```

Now you have a copy of RawPHP and it's working fine, you'll need to setup your RawPHP database to complete this installation. The full [installation instructions are here](https://github.com/rawphp-framework/rawphp-docs/blob/master/docs/start/installation.md) . Enjoy.

## Documentation
Below is the  link to the documentation and tutorials

- [Documentation](https://github.com/rawphp-framework/rawphp-docs)
- [Sample blog application tutorial](https://github.com/rawphp-framework/RawPHP-docs/blob/master/docs/tutorial/first-app.md)
- Build a Job recruitment platform using this [Youtube Video Tutorials](https://www.youtube.com/watch?v=hzRXYrdR4m0&list=PLnBvgoOXZNCM_cxMH8rhLVch_YQbUL5el)
- [Website](https://github.com/rawphp-framework/rawphp-website)


## Contributing
If you make any tutorial on RawPHP, please [report it as an issue](https://github.com/rawphp-framework/rawphp/issues) so we can add it to one of the resources. 

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.


## Security

If you discover security related issues, please use the issue tracker (for now).


## License

The RawPHP Framework is licensed under the MIT license. See [License File](LICENSE.md) for more information.
