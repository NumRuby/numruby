# NumRuby

**Under construction**

NumRuby is the umbrella gem for a Ruby scientific computing ecosystem inspired by [NumPy](https://github.com/numpy) and [SciPy](https://github.com/scipy).
It provides a unified namespace for array, linear algebra, statistics, plotting, and other scientific libraries.

## Modules

Planned usage of [Ruby Numo (NUmerical MOdule)](https://github.com/ruby-numo) for parts of NumRuby.

- `numo-narray` : Core multidimensional arrays
- `numo-linalg` : Linear algebra
- `numruby-ufunc` : Elementwise functions & broadcasting
- `numruby-stats` : Statistical & probability routines
- `numruby-plot` : Plotting & visualization

## Vision

Provide a unified namespace for math, data, and scientific computing in Ruby,
making it easy for researchers, educators, and data scientists to use Ruby
similarly to Python’s scientific stack.

## Installation

Install the gem and add to the application's Gemfile by executing:

```sh
bundle add numruby
```

If bundler is not being used to manage dependencies, install the gem by executing:

```sh
gem install numruby
```

## Usage

TODO

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/numruby/numruby. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/numruby/numruby/blob/main/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Code of Conduct

Everyone interacting in the Numruby project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/numruby/numruby/blob/main/CODE_OF_CONDUCT.md).
