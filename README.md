# TopDown

TopDown is a Ruby PEG-like top-down recursive decent parser library. The parser grammar is defined with Ruby object code (similar to JSON). Also included is a library to parse PEG grammars with TopDown.

## Status

This library is fairly complete and usable, but is lacking documentation and examples. I most likely will no longer develop this project, since I only use it to bootstrap chpeg (http://github.com/ChrisHixon/chpeg). I started developing this parser before I discovered PEG. After discovering PEG and working on the chpeg library, I would probably change many things about TopDown to be more like chpeg.

## Installation

The easiest way to install TopDown is as a RubyGem:

    $ umask 0022 # important if you have a restrictive umask
    $ gem build ch-top_down.gemspec
    $ sudo gem install ch-top_down-0.7.0.gem
  
## Examples

Currently, there are no simple examples. I use TopDown's PEG parser to bootstrap chpeg, a C PEG parser/compiler library (http://github.com/ChrisHixon/chpeg, see bootstrap directory).
  
## TODO

Documentation, examples.
