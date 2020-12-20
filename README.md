# Liquid Thousands Separated Filter
> Jekyll Liquid filter to add thousands separator to a number

[![Ruby - >=2.6](https://img.shields.io/badge/Ruby->%3D2.6-blue?logo=ruby&logoColor=white)](https://ruby-lang.org)
[![License - CC0 Universal](https://img.shields.io/badge/License-CC0_Universal-blue)](#license)

A basic [Liquid](http://docs.shopify.com/themes/liquid-documentation/basics) / [Jekyll](http://jekyllrb.com) filter that adds thousands-separators to a number. The default separator is a comma.


## Sample usage

### Basic

```liquid
{{ "123456789" | thousands_separated }}
```
```
123,456,789
```

### Custom separator

```liquid
{{ "123456789" | thousands_separated: " " }}
```
```
123 456 789
```


## Installation

You can do this in GitHub without cloning this project.
 
1. Create a `_plugins` directory in your Jekyll project.
2. Create a file at the path `_plugins/thousands-separated-filter.rb`.
3. Copy the contents of [thousands-separated-filter.rb](/thousands-separated-filter.rb) to that file.


## Usage

```liquid
{{ value | thousands_separated }}
```


## License

License under [CC0 Universal (public domain)](https://creativecommons.org/publicdomain/zero/1.0/deed.en) Matt Gemmell - [mattgemmell.com](http://mattgemmell.com) - [@mattgemmell](http://twitter.com/mattgemmell).

On this fork by [@MichaelCurrin](https://github.com/MichaelCurrin) - doc changes and code style changes 
