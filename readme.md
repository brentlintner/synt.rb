## Synt.rb [![Gem Version](https://badge.fury.io/rb/synt.svg)](http://badge.fury.io/rb/synt)

Calculates the similarity between two pieces of Ruby code.

**NOTICE**

This project is not actively maintained, and is based on an
old implementation of the [Synt](https://github.com/brentlintner/synt) project.

If you want to help maintain this repo, please open an issue and ask!

### Installation

    gem install synt

### Usage

    synt -h

#### Comparing Two Ruby Files

    synt -c lib/foo.rb -t lib/bar.rb

### Hacking

    ./bin/dev-setup

### Testing

    ./bin/test
