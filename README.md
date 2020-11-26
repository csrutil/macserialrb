# Macserialrb

[![Build Status](https://travis-ci.org/csrutil/macserialrb.svg?branch=main)](https://travis-ci.org/csrutil/macserialrb)
[![Gem Version](https://badge.fury.io/rb/macserialrb.svg)](https://badge.fury.io/rb/macserialrb)
![](https://ruby-gem-downloads-badge.herokuapp.com/macserialrb)

This is the Ruby version of the macserial, you can check the [source](https://github.com/acidanthera/OpenCorePkg/tree/master/Utilities/macserial) here

## Usage

List all the models

```bash
$ macserialrb -l
MacBook1,1
MacBook10,1
MacBook2,1
...
```

Generate SystemSerialNumber and MLB

```ruby
$ macserialrb -m iMac19,1

iMac19,1 macserial info

productName: iMac19,1
SystemSerialNumber: C02DX0VSJV3Q
MLB: C02053301CDLNV9CB
```

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'macserialrb'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install macserialrb


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/csrutil/macserialrb. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/csrutil/macserialrb/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Macserialrb project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/csrutil/macserialrb/blob/master/CODE_OF_CONDUCT.md).

## Credits

- https://github.com/acidanthera/OpenCorePkg
