# testing-php
Composer package for PHP unit testing tools, using Phing for Jenkins or local development

Use this project purely for the dependencies it includes, or use the build file to make use of the default commands.


# Install Phing:

Install phing globally using the following commands

```sh
   pear channel-discover pear.phing.info
   pear installs phing/phing
```


# Default Configuration

The default build.xml exposes the following commands: 
  - phpunit
  - phpunit-ci
  - phpcs
  - phpcs-ci
  - phpcbf
  - lint
  - phpcpd
  - phpcpd-ci
  - phpmd
  - phpmd-ci
  - phpdox

You can 
