# phparsenal roadmap

[![Join the chat at https://gitter.im/phparsenal/roadmap](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/phparsenal/roadmap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**We have started on our first project: [fast forward](https://github.com/phparsenal/fast-forward)**

First repository to share some things, getting started.

Our IRC channel is #ormcollab on freenode. You can use the [webchat](http://webchat.freenode.net/?channels=ormcollab) or any other client.

[Links/Resources](https://github.com/phparsenal/roadmap/wiki/Links)

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
