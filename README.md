# phparsenal roadmap
First place to share some things, getting started

## Proposal for collaboration guidelines

### Version control
Git as a DVCS and a central Github repository for the group is hard to argue with.

Use [semantic versioning](http://semver.org/) when tagging releases.

### PHP
Generally use php-fig's PSRs as they currently reflect PHP best practices.

- Follow the [PSR-2 coding style guide](http://www.php-fig.org/psr/psr-2/)
  - You can use the [PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) to automatically format your code. Use pre-commit or checkout hooks.
- Follow the [PSR-4 autoloader standard](http://www.php-fig.org/psr/psr-4/)
- Use [Composer](https://getcomposer.org/) to manage dependencies and offer our projects as libraries
- Use unit testing
  - Write tests for PHPunit, ideally before even writing the functionality
  - Use the free [Travis-CI](https://travis-ci.org/) service to report on build/test status
