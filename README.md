# Sitegeist.Kaleidoscope.Wff

## Tools to better understand the Sitegeist.Kaleidoscope image rendering

This package adds a debug mode for Sitegeist.Kaleidoscope that replaces all
imagesSources in with DummyImageSources while preserving existing Dimensions.

That way the resulting image rendering and the chosen sizes can be evaluated 
without the Sitegeist.Monocle styleguide any by using the same rendering pathes 
as the actual website. 

### Authors & Sponsors

* Martin Ficzel - ficzel@sitegeist.de

*The development and the public-releases of this package is generously sponsored
by our employer http://www.sitegeist.de.*

## Installation

Sitegeist.Kaleidoscope.Wtf is available via packagist run `composer require --dev sitegeist/kaleidoscope-wtf`.
We use semantic versioning so every breaking change will increase the major-version number.

!!! This should only be installed temporarily or as dev-dependency. This code does should not be deployed to production servers !!!

## Usage 

By default enforcing of DummyImages is disabled and has to be enabled via setting.

```
Sitegeist:
  Kaleidoscope:
    Wtf:
      enforceDummyImages: true
```

## Contribution

We will gladly accept contributions. Please send us pull requests.
