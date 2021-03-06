# Atom Autocomplete+ Ruby Suggestions
[![Dependency status](https://david-dm.org/ianhattendorf/autocomplete-ruby.svg)](https://david-dm.org/ianhattendorf/autocomplete-ruby)
[![GitHub version](https://badge.fury.io/gh/ianhattendorf%2Fautocomplete-ruby.svg)](http://badge.fury.io/gh/ianhattendorf%2Fautocomplete-ruby)

Provides intelligent code completion for Ruby. Requires [RSense](https://github.com/rsense/rsense) and [Autocomplete+](https://github.com/atom-community/autocomplete-plus).

## Status
Currently pre-alpha, buggy and not fully implemented. All help is welcome.

## Why?
Because I wanted Ruby code completion in Atom and [atom-rsense](https://github.com/rsense/atom-rsense) hasn't been updated since June 2014, which is a long time for an Atom package. It's currently broken and I didn't like the dependency on Opal, as much as I enjoy Ruby, so I decided to create this.

## Installation
Make sure you have Java installed on your machine.

Install required gems and Atom packages:
```shell
$ gem install rsense
$ apm install autocomplete-plus (is preinstalled with Atom)
```

If you need to set up the rsense path, execute `gem environment`: Then take the `EXECUTABLE DIRECTORY`, add `rsense` and put this into the rsense executable path.

## Usage
Just type some stuff, and autocomplete+ will automatically show you some suggestions.

Note: If you use Winows, it might take about 10 seconds after the first suggestions pop up before rsense will give you any suggestions.

## Bugs
A lot. If you're brave enough to try this out and notice any specifically, feel free to open an issue or even better submit a pull request.

## Development
Clone the repository into your working directory:
```shell
$ git clone git@github.com:ianhattendorf/autocomplete-ruby.git
```

Install dependencies:
```shell
$ cd autocomplete-ruby
$ apm install
```

Link to Atom as a dev package:
```shell
$ apm link --dev
```

Feel free to fork it and submit a pull request for any changes you make.
