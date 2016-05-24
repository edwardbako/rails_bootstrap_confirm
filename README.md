# RailsBootstrapConfirm

This is a small gem that replaces browser standard confirmation dialogue to pretty Bootstrap styled
modal dialogue.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rails_bootstrap_confirm'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rails_bootstrap_confirm

## Usage

```ruby
  link_to 'Name', some_action_path, data: {confirm: 'Are you sure?',
                                           header: 'Confirm, please',
                                           cancel: 'No',
                                           ok: 'Yes'}
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to
run the tests. You can also run `bin/console` for an interactive prompt that will allow you to
experiment.

## Contributing

Bug reports and pull requests are welcome on GitHub 
at https://github.com/edwardbako/rails_bootstrap_confirm. This project is intended to be a safe,
welcoming space for collaboration, and contributors are expected to adhere to the 
[Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the
 [MIT License](http://opensource.org/licenses/MIT).

