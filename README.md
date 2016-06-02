# Local FastImage

This is a fork of the [FastImage](https://github.com/sdsykes/fastimage) gem.

It features the following differences:

* Removal of all remote image handling code
* Minor changes to code organization

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'local-fastimage', require: 'fastimage'
```

And then execute:

    $ bundle


If you are using Bundler's autorequire, your good to go. Otherwise make sure to
`require "fastimage"`.

Or install it yourself as:

    $ gem install local-fastimage

Again, make sure to `require "fastimage"`.



## Usage

See [README.textile](README.textile) for more documentation. Everything should
work as advertised, expect for remote images of course.



## License

MIT, see file [MIT-LICENSE](MIT-LICENSE)
