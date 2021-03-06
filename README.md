# Fixx

Fixx is a command line tool that will help you grep through those horrible fix message logs.

## Installation

Install it yourself as:

    $ gem install fixx

## Usage

```
Usage: fixx [options] [files]
Fixx helps you grep through your icky fix message logs.

Specific options:
        --show-heartbeats            Output 35=0 rows (filtered out by default).
        --raw                        Output rows in raw format.
    -m, --message-type TYPE          Filter for a specific message type.
    -c, --contains-field NUM         Filter for messages that contain a particular field.
    -e, --extract-field NUM          Extract a particular field.
    -h, --help                       You're looking at it!
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cfox/fixx. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Fixx project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/cfox/fixx/blob/master/CODE_OF_CONDUCT.md).
