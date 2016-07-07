# SchoetlrGem

This gem contains a "hello world!" method as well as a rock paper scissors game.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'schoetlr_gem'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install schoetlr_gem

## Usage

to call "hello world!", use SchoetlrGem.hello

to play tic tac toe, create a new game object using SchoetlrGem::Game.new, follow the instructions, then run <game_object>.play to play the game.

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/schoetlr_gem. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
