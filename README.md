# A modern space cadet

[![Build Status](https://travis-ci.org/smh/puppet-modern-spacecadet.png?branch=master)](https://travis-ci.org/smh/puppet-modern-spacecadet)

Sets up your keyboard along the lines of [the modern space
cadet](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/)

## Usage

```puppet
include modern_space_cadet
```

## Required Puppet Modules

* `boxen`
* `osx`
* `glarizza/puppet-property_list_key`
* `boxen/puppet-pckeyboardhack`
* `boxen/puppet-keyremap4macbook`

## Development

Write code. Run `script/cibuild` to test it. Check the `script`
directory for other useful tools.
