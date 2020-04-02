# Liquid Thousands Separated Filter


A basic [Liquid](http://docs.shopify.com/themes/liquid-documentation/basics) / [Jekyll](http://jekyllrb.com) filter that adds thousands-separators to a number. The default separator is a comma.


## Sample usage

### Basic

    {{ "123456789" | thousands_separated }}
    
Renders as:

    123,456,789

### Custom separator

    {{ "123456789" | thousands_separated: " " }}

    123 456 789


## Installation

Create `_plugins` directory.

Create a file at path `_plugins/thousands-separated-filter.rb`.

Copy contents of [thousands-separated-filter.rb](/thousands-separated-filter.rb) to that file.


## Usage

    {{ value | thousands_separated }}


## License


By Matt Gemmell - [mattgemmell.com](http://mattgemmell.com) - [@mattgemmell](http://twitter.com/mattgemmell)

License: [CC0 Universal (public domain)](https://creativecommons.org/publicdomain/zero/1.0/deed.en)
