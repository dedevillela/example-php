[Codecov][1] PHP Example
========================
[![Codecov](https://img.shields.io/codecov/c/github/dedevillela/example-php.svg)]() [![Scrutinizer](https://img.shields.io/scrutinizer/g/dedevillela/example-php.svg)]() [![Scrutinizer Build](https://img.shields.io/scrutinizer/build/g/dedevillela/example-php.svg)]() [![Scrutinizer Coverage](https://img.shields.io/scrutinizer/coverage/g/dedevillela/example-php.svg)](https://scrutinizer-ci.com/g/dedevillela/Simple-Featured-Image-Column/) [![Code Intelligence Status](https://scrutinizer-ci.com/g/dedevillela/example-php/badges/code-intelligence.svg?b=master)](https://scrutinizer-ci.com/code-intelligence) [![Build Status](https://travis-ci.org/dedevillela/example-php.svg?branch=master)](https://travis-ci.org/dedevillela/example-php)  [![Maintainability](https://api.codeclimate.com/v1/badges/749af6afa84d34e8871d/maintainability)](https://codeclimate.com/github/dedevillela/example-php/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/749af6afa84d34e8871d/test_coverage)](https://codeclimate.com/github/dedevillela/example-php/test_coverage)

1. Collect coverage reports `vendor/bin/phpunit --coverage-clover=coverage.xml`, [see here][2]
2. Call `bash <(curl -s https://codecov.io/bash)` at the end of your CI build, [see here][3]
  - [Learn how to include your upload repository token][4]

> Contact Codecov support team for help :thumbsup: https://codecov.io/support

# Frequently Asked Questions

####❔Using phpunit.xml.dist?
Start tracking coverage metrics by adding a coverage logger:

```xml
<phpunit>
  ...
  <logging>
        <log type="coverage-clover" target="clover.xml"/>
    </logging>
</phpunit>
```

####❔I don't see one or more files?

Codecov will only show files that have lines covered (hit or miss). If your file has no statments it will not show up in Codecov until you add some. Go get em' tiger!


[1]: https://codecov.io/
[2]: https://github.com/codecov/example-php/blob/master/.travis.yml#L15
[3]: https://github.com/codecov/example-php/blob/master/.travis.yml#L18
[4]: http://docs.codecov.io/docs/about-the-codecov-bash-uploader#section-upload-token
